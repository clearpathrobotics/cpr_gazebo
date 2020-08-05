cmake_minimum_required(VERSION 3.0.2)
project(cpr_inspection_gazebo)

find_package(catkin REQUIRED COMPONENTS)

catkin_package()

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)

install(DIRECTORY launch meshes urdf worlds models
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
  PATTERN "*~" EXCLUDE)
