cmake_minimum_required(VERSION 3.0.2)
project(cpr_inspection_gazebo)

find_package(catkin REQUIRED COMPONENTS)

catkin_package()

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)

install(DIRECTORY images launch meshes models rviz scripts urdf worlds
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
  PATTERN "*~" EXCLUDE)

install(FILES model.config
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
