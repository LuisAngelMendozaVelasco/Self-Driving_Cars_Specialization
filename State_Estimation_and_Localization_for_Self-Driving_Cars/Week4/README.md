# Module 4: LIDAR Sensing

LIDAR (light detection and ranging) sensing is an enabling technology for self-driving vehicles. LIDAR sensors can ‘see’ farther than cameras and are able to provide accurate range information. This module develops a basic LIDAR sensor model and explores how LIDAR data can be used to produce point clouds (collections of 3D points in a specific reference frame). Learners will examine ways in which two LIDAR point clouds can be registered, or aligned, in order to determine how the pose of the vehicle has changed with time (i.e., the transformation between two local reference frames).

## Learning Objectives

- Explain how LIDAR sensors are able to generate range data from time-of-flight measurements
- Understand inverse and forward sensor models for a basic scanning LIDAR
- Apply standard transfomations (translation, rotation, and scaling) to LIDAR point cloud data
- Summarize how the problem of motion distortion can affect LIDAR scans acquired from a moving vehicle
- Utilize the iterative closest point (ICP) algorithm to align point clouds from consecutive LIDAR scans

## LIDAR Sensing

- [Video - Lesson 1: Light Detection and Ranging Sensors](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/3NXgp/lesson-1-light-detection-and-ranging-sensors)

- [Reading - Lesson 1: Light Detection and Ranging Sensors](./Readings/C2M4L1-Light_Detection_and_Ranging_Sensors.pdf)

- [Reading - Lesson 1 Supplementary Reading: Light Detection and Ranging Sensors](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/JZduj/lesson-1-supplementary-reading-light-detection-and-ranging-sensors)

- [Video - Lesson 2: LIDAR Sensor Models and Point Clouds](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/Huunu/lesson-2-lidar-sensor-models-and-point-clouds)

- [Reading - Lesson 2: LIDAR Sensor Models and Point Clouds](./Readings/C2M4L2-LIDAR_Sensor_Models_and_Point_Clouds.pdf)

- [Reading - Lesson 2 Supplementary Reading: LIDAR Sensor Models and Point Clouds](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/x5Pb8/lesson-2-supplementary-reading-lidar-sensor-models-and-point-clouds)

- [Video - Lesson 3: Pose Estimation from LIDAR Data](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/XE9kZ/lesson-3-pose-estimation-from-lidar-data)

- [Reading - Lesson 3: Pose Estimation from LIDAR Data](./Readings/C2M4L3-Pose_Estimation_from_LIDAR_Data.pdf)

- [Reading - Lesson 3 Supplementary Reading: Pose Estimation from LIDAR Data](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/4u4Pu/lesson-3-supplementary-reading-pose-estimation-from-lidar-data)

## Learn from Industry Experts

- [Video - Optimizing State Estimation](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/lJkFG/optimizing-state-estimation)