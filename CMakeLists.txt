cmake_minimum_required(VERSION 3.0.2)
project(mecanum_robot)

find_package(catkin REQUIRED COMPONENTS roscpp rospy actionlib move_base_msgs std_msgs roslaunch)

catkin_package()

include_directories(${catkin_INCLUDE_DIRS})
