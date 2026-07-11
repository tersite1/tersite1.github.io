---
name: Forest Carbon Estimation (Graduation Project)
category: personal
tools: [SLAM, Point Cloud, Sensor Fusion, Remote Sensing]
image: /assets/img/p-carbon.png
description: Graduation project. End-to-end LiDAR-inertial SLAM (DLIO) with Mid-70 LiDAR and IMU calibration to estimate forest carbon sequestration.
---

## Forest Carbon Estimation via LiDAR-Inertial SLAM

Graduation project (Best Project). I built an end-to-end LiDAR-inertial SLAM pipeline based on DLIO, mounting a Livox Mid-70 LiDAR, an IMU, and a Jetson Nano on a drone and calibrating the sensors together. Flying over a forest, the system reconstructs a dense 3D point cloud; from it I detect and count individual trees with Euclidean clustering and estimate the forest's carbon sequestration.

<figure class="pd-fig"><img src="/assets/img/g-carbonrig-3.png" alt=""><figcaption>Individual tree detection from the reconstructed point cloud</figcaption></figure>

<figure class="pd-fig"><img src="/assets/img/g-carbon-gif.gif" alt=""><figcaption>Counting trees with Euclidean clustering</figcaption></figure>

<figure class="pd-fig"><img src="/assets/img/g-carbonrig-1.png" alt=""><figcaption>Drone sensor rig: Livox Mid-70 LiDAR, IMU, GoPro, and Jetson Nano</figcaption></figure>

<figure class="pd-fig"><img src="/assets/img/g-carbon-3.png" alt=""><figcaption>The scanning drone with the Livox Mid-70 mounted</figcaption></figure>

<figure class="pd-fig"><img src="/assets/img/g-carbon-1.png" alt=""><figcaption>LiDAR-acquired vs. camera-only (NeRF) reconstruction</figcaption></figure>

<figure class="pd-fig"><img src="/assets/img/g-carbon-2.png" alt=""><figcaption>Data acquisition site and reference setup</figcaption></figure>

