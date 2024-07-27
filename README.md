# Maze-Solver-Line-Follower
This repository contains the code and schematics for an Arduino-based line-following robot. The robot uses infrared sensors to detect the line and a PID control algorithm to follow the path accurately.

Features:
Real-time line detection using infrared sensors
PID control algorithm for smooth and precise path tracking
Dynamic motor speed adjustment based on sensor input
User-friendly and efficient implementation in C++

Hardware Components:
Arduino Uno
Infrared sensors (5 for line detection)
Motor drivers (H-bridge or similar)
Motors and wheels
Chassis for mounting components

Software Techniques:
C++ programming for real-time data acquisition and processing
Implementation of a PID control algorithm for motor speed control
Sensor data filtering and error calculation for accurate line following

Usage:
Assemble the robot chassis and mount the hardware components as per the schematic.
Power on the system.
Place the robot on a track with a defined line to follow.
The robot will automatically adjust its path using the PID control algorithm based on sensor input.
