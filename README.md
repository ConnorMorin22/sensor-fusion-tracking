# Sensor Fusion & Object Tracking 🎯

This project implements a **multi-sensor fusion and object tracking system** using **camera and LiDAR data**.  
It demonstrates how to integrate multiple perception modalities and apply **Kalman Filters** for motion estimation, prediction, and tracking in robotics and autonomous driving contexts.

---

## 🧠 Overview

- **Goal:** Fuse data from LiDAR and camera sensors to track dynamic objects in real-time.  
- **Tech stack:** C++, Python, ROS, Eigen, OpenCV.  
- **Core concepts:** Sensor calibration, coordinate transformations, object detection, Kalman Filters.

---

## ⚙️ Current Progress

- [x] LiDAR point cloud preprocessing and clustering  
- [x] Camera-based object detection pipeline  
- [ ] Data association and multi-sensor fusion  
- [ ] Kalman Filter integration for trajectory prediction  
- [ ] Visualization and performance benchmarking  

---

## 📦 Installation

```bash
git clone https://github.com/ConnorMorin22/sensor-fusion-tracking.git
cd sensor-fusion-tracking
mkdir build && cd build
cmake ..
make
