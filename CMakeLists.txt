cmake_minimum_required(VERSION 2.8.3)
project(my_r12_description)

find_package(catkin REQUIRED COMPONENTS
  controller_manager
  gazebo_ros
  joint_state_publisher
  robot_state_publisher
  rospy
  rviz
)

catkin_package(
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)

