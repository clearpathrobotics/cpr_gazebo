cmake_minimum_required(VERSION 3.0.2)
project(cpr_agriculture_gazebo)

find_package(catkin REQUIRED COMPONENTS)

catkin_package()

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)

install(DIRECTORY images launch meshes rviz scripts urdf worlds
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

install(FILES model.config
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
