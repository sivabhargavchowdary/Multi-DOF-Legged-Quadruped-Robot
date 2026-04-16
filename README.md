# Multi-DOF-Legged-Quadruped-Robot
ROS-based quadruped robot with IMU stabilization, Lidar SLAM, and joystick control
# 🐕 Quadruped Dog Robot (ROS-Based)

## 🚀 Overview

This project is a 12-DOF quadruped robot built using Raspberry Pi and ROS.
It supports joystick-based control and autonomous navigation using Lidar.

## 🎯 Features

* Joystick control for walking
* Lidar-based mapping (SLAM)
* IMU-based orientation sensing
* ROS-based modular control

## 🔧 Hardware

* Raspberry Pi 4
* PCA9685 Servo Driver
* 12x Servo Motors
* MPU6050 (IMU)
* YDLidar

## 💻 Software

* ROS Noetic / ROS2 Humble
* Python

## ▶️ How to Run

```bash
cd ~/catkin_ws
catkin_make
source devel/setup.bash
roslaunch dog_robot manual.launch
```

## ⚠️ Challenges

* Servo jitter due to power issues
* IMU noise filtering
* ROS node synchronization

## 🔮 Future Work

* Autonomous navigation
* Better gait optimization
