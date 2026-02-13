# Intelligent Surveillance & Rescue UAV

An edge AI-based autonomous drone system designed to perform surveillance and rescue missions in GPS-denied environments.

---

## Overview

This project builds a self-reliant UAV system capable of operating in environments where GPS signals are weak, blocked, or unavailable. The system integrates visual SLAM, sensor fusion, and onboard edge processing to enable stable navigation, real-time mapping, and autonomous decision-making.

The architecture combines ROS2-based autonomy, PX4 flight control, MAVLink communication, and stereo vision for reliable aerial operations in disaster zones, dense urban environments, and signal-contested areas.

---

## Problem Statement

Most UAV systems depend heavily on GPS for localization and mission stability. In disaster zones, indoor spaces, urban canyons, or jamming-prone environments, GPS becomes unreliable, severely limiting drone effectiveness during surveillance and rescue missions.

This project addresses the challenge of enabling reliable drone operation without continuous GPS dependency.

---

## Proposed Solution

The system uses:

- Visual SLAM for GPS-denied localization
- Stereo vision (RealSense) for depth and mapping
- Sensor fusion (Camera + IMU)
- Edge AI processing for real-time perception
- ROS2-based autonomy framework
- PX4 flight controller for stable flight control
- MAVLink protocol for communication

All critical processing is performed onboard to reduce latency and cloud dependency.

---

## System Architecture

The architecture consists of:

- Operator Ground Station (Telemetry & Mission Control)
- Onboard Edge AI Processing Unit
- Visual SLAM Module
- Stereo Vision Camera (RGB-D)
- PX4 Flight Controller
- MAVLink Communication Layer
- Validation & Logging Framework

The drone performs real-time mapping, localization, and decision-making before transmitting mission data to the ground station.

---

## Folder Structure

