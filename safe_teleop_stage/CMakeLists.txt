cmake_minimum_required(VERSION 2.8.3)
project(safe_teleop_stage)

find_package(catkin REQUIRED COMPONENTS)
catkin_package(CATKIN_DEPENDS)

install(DIRECTORY launch config
  DESTINATION
  ${CATKIN_PACKAGE_SHARE_DESTINATION}
  USE_SOURCE_PERMISSIONS
  )
