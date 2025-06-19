# LrnRosSerialStm32F4
This project implements a ROS Serial interface to enable communication between an STM32F4 microcontroller and a Jetson Nano or standard Linux-based laptop. It is designed as part of a larger robotics system to enable real-time data acquisition and processing from various onboard sensors.
Publish this sensor data as ROS topics for use in higher-level robotic computation (e.g., navigation, SLAM, control)

USED:-
ROS Noetic
Python / C++ for ROS nodes (Jetson/Laptop side)

bash:
sudo apt install ros-noetic-rosserial ros-noetic-rosserial-python

source devel/setup.bash

rosrun rosserial_python serial_node.py _port:=/dev/ttyUSB0 _baud:=57600
