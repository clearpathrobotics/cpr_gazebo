cmake_minimum_required(VERSION 3.0.2)
project(gazebo_race_modules)

find_package(catkin REQUIRED COMPONENTS)

catkin_package()

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)

install(DIRECTORY docs launch meshes urdf worlds
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
