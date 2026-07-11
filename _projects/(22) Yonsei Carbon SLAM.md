---
name: Forest Carbon Estimation via LiDAR-Inertial SLAM
category: personal
tools: [LiDAR SLAM, Point Cloud, Sensor Fusion, Remote Sensing]
video: /assets/img/p-carbon.mp4
image: /assets/img/p-carbon.png
description: Graduation project. End-to-end LiDAR-inertial SLAM (DLIO) with Mid-70 LiDAR and IMU calibration to estimate forest carbon sequestration.
---

## Forest Carbon Estimation via LiDAR-Inertial SLAM

Graduation project (Best Project). I built an end-to-end LiDAR-inertial SLAM pipeline based on DLIO, mounting a Livox Mid-70 LiDAR, an IMU, and a Jetson Nano on a drone and calibrating the sensors together.

Flying over a forest, the system reconstructs a dense 3D point cloud. From the reconstruction I segment and count individual trees with Euclidean clustering, then estimate the forest's carbon sequestration from the counted canopy.

![Sensor rig](/assets/img/g-carbonrig-1.png)
![Drone platform](/assets/img/g-carbon-1.png)
![Field capture](/assets/img/g-carbon-2.png)
![Reconstruction](/assets/img/g-carbon-3.png)
![Processing](/assets/img/g-carbonrig-2.png)
![Result](/assets/img/g-carbonrig-3.png)
![Tree counting via Euclidean clustering](/assets/img/g-carbon-gif.gif)
