# Module 3: GNSS/INS Sensing for Pose Estimation

To navigate reliably, autonomous vehicles require an estimate of their pose (position and orientation) in the world (and on the road) at all times. Much like for modern aircraft, this information can be derived from a combination of GPS measurements and inertial navigation system (INS) data. This module introduces sensor models for inertial measurement units and GPS (and, more broadly, GNSS) receivers; performance and noise characteristics are reviewed. The module describes ways in which the two sensor systems can be used in combination to provide accurate and robust vehicle pose estimates.

## Learning Objectives

- Explain the operation of the two most common sensors used for pose estimation in autonomous driving, inertial meaurement units and GNSS receivers.
- Understand the concept of coordinate acceleration and the fundamental equation of inertial navigation.
- Apply gyroscope and accelerometer measurement models in the context of navigation.
- Describe the process of trilateration and justify why four satellites must be visible to obtain a 3D position fix from a GPS (GNSS) receiver.
- Understand why ionospheric delays and multipath effects can degrade the performance of GPS.

## GNSS/INS Sensing for Pose Estimation

- [Video - Lesson 1: 3D Geometry and Reference Frames](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/ccy3B/lesson-1-3d-geometry-and-reference-frames)

- [Reading - Lesson 1: 3D Geometry and Reference Frames](./Readings/C2M3L1-3D_Geometry_and_Refrence_Frames.pdf)

- [Reading - Lesson 1 Supplementary Reading: 3D Geometry and Reference Frames](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/4rJ2h/lesson-1-supplementary-reading-3d-geometry-and-reference-frames)

- [Video - Lesson 2: The Inertial Measurement Unit (IMU)](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/TBMU9/lesson-2-the-inertial-measurement-unit-imu)

- [Reading - Lesson 2: The Inertial Measurement Unit (IMU)](./Readings/C2M3L2-The_Inertial_Measurement_Unit.pdf)

- [Reading - Lesson 2 Supplementary Reading: The Inertial Measurement Unit (IMU)](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/FZdrA/lesson-2-supplementary-reading-the-inertial-measurement-unit-imu)

- [Video - Lesson 3: The Global Navigation Satellite Systems (GNSS)](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/TDlnE/lesson-3-the-global-navigation-satellite-systems-gnss)

- [Reading - Lesson 3: The Global Navigation Satellite Systems (GNSS)](./Readings/C2M3L3-Global_Navigation_Satellite_Systems.pdf)

- [Reading - Lesson 3 Supplementary Reading: The Global Navigation Satellite System (GNSS)](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/q2Z7F/lesson-3-supplementary-reading-the-global-navigation-satellite-system-gnss)

## Learn from Industry Experts

- [Video - Why Sensor Fusion?](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/HCP35/why-sensor-fusion)