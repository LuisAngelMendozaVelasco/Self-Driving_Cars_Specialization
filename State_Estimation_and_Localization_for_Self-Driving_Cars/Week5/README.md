# Module 5: Putting It together - An Autonomous Vehicle State Estimator

This module combines materials from Modules 1-4 together, with the goal of developing a full vehicle state estimator. Learners will build, using data from the CARLA simulator, an error-state extended Kalman filter-based estimator that incorporates GPS, IMU, and LIDAR measurements to determine the vehicle position and orientation on the road at a high update rate. There will be an opportunity to observe what happens to the quality of the state estimate when one or more of the sensors either 'drop out' or are disabled.

## Learning Objectives

- Apply filtering-based state estimation to determine the pose of a vehicle on the roadway
- Use LIDAR scan registration (to an existing map) to improve state estimates
- Test the effects of the loss of one or more sensors on the vehicle pose estimate

## State Estimation in Practice

- [Video - Lesson 1: State Estimation in Practice](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/VihNN/lesson-1-state-estimation-in-practice)

- [Reading - Lesson 1: State Estimation in Practice](./Readings/C2M5L1-State_Estimation_in_Practice.pdf)

- [Video - Lesson 2: Multisensor Fusion for State Estimation](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/2imn3/lesson-2-multisensor-fusion-for-state-estimation)

- [Reading - Lesson 2: Multisensor Fusion for State Estimation](./Readings/C2M5L2-Multisensor_Fusion_for_State_Estimation.pdf)

- [Reading - Lesson 2 Supplementary Reading: Multisensor Fusion for State Estimation](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/MNnzM/lesson-2-supplementary-reading-multisensor-fusion-for-state-estimation)

- [Video - Lesson 3: Sensor Calibration - A Necessary Evil](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/jPb2Y/lesson-3-sensor-calibration-a-necessary-evil)

- [Reading - Lesson 3: Sensor Calibration - A Necessary Evil](./Readings/C2M5L3-Sensor_Calibration.pdf)

- [Reading - Lesson 3 Supplementary Reading: Sensor Calibration - A Necessary Evil](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/VbcgB/lesson-3-supplementary-reading-sensor-calibration-a-necessary-evil)

- [Video - Lesson 4: Loss of One or More Sensors](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/FfCsO/lesson-4-loss-of-one-or-more-sensors)

- [Reading - Lesson 4: Loss of One or More Sensors](./Readings/C2M5L4-Loss_of_One_or_more_Senssors.pdf)

## Learn from Industry Experts

- [Video - The Challenges of State Estimation](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/4dQLf/the-challenges-of-state-estimation)

## Final Project: Vehicle State Estimation on a Roadway

- [Video - Final Lesson: Project Overview](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/XwBK1/final-lesson-project-overview)

- [Lab - Final Project: Vehicle State Estimation on a Roadway](./Labs/es_ekf.ipynb)

- [Video - Final Project Solution [LOCKED]](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/Myx6X/final-project-solution-locked)

## Lesson 3 - Congratulations!

- [Video - Congratulations on Completing Course 2!](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/QXgFg/congratulations-on-completing-course-2)