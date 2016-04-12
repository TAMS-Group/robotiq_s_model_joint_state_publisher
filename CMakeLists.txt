cmake_minimum_required(VERSION 2.8.3)
project(robotiq_s_model_joint_state_publisher)

find_package(catkin REQUIRED COMPONENTS
  robotiq_s_model_control
  rospy
  sensor_msgs
)

catkin_package(
  CATKIN_DEPENDS sensor_msgs
)


