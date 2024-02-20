# Module 2: State Estimation - Linear and Nonlinear Kalman Filters

Any engineer working on autonomous vehicles must understand the Kalman filter, first described in a paper by Rudolf Kalman in 1960. The filter has been recognized as one of the top 10 algorithms of the 20th century, is implemented in software that runs on your smartphone and on modern jet aircraft, and was crucial to enabling the Apollo spacecraft to reach the moon. This module derives the Kalman filter equations from a least squares perspective, for linear systems. The module also examines why the Kalman filter is the best linear unbiased estimator (that is, it is optimal in the linear case). The Kalman filter, as originally published, is a linear algorithm; however, all systems in practice are nonlinear to some degree. Shortly after the Kalman filter was developed, it was extended to nonlinear systems, resulting in an algorithm now called the ‘extended’ Kalman filter, or EKF. The EKF is the ‘bread and butter’ of state estimators, and should be in every engineer’s toolbox. This module explains how the EKF operates (i.e., through linearization) and discusses its relationship to the original Kalman filter. The module also provides an overview of the unscented Kalman filter, or UKF, a more recently developed and very popular member of the Kalman filter family.

## Learning Objectives

- Describe the relationship between least squares and the linear Kalman filter
- Explain the (in)sensitivity of the Kalman filter to new data and the need for process noise
- Describe how the linear Kalman filter can be extended to nonlinear systems via linearization
- Describe how the EKF uses first-order linearization to turn a nonlinear problem into a linear one
- Contrast the linearization approach of the EKF with that of the UKF, and explain why the UKF is superior for many problems
- Assess the performance of the extended Kalman filter and its variants

## The Linear Kalman Filter

- [Video - Lesson 1: The (Linear) Kalman Filter](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/7DFmY/lesson-1-the-linear-kalman-filter)

- [Reading - Lesson 1: The (Linear) Kalman Filter](./Readings/C2M2L1-The_Kalman_Filter.pdf)

- [Reading - Lesson 1 Supplementary Reading: The Linear Kalman Filter](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/akBXs/lesson-1-supplementary-reading-the-linear-kalman-filter)

- [Video - Lesson 2: Kalman Filter and The Bias BLUEs](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/oSdr9/lesson-2-kalman-filter-and-the-bias-blues)

- [Reading - Lesson 2: Kalman Filter and The Bias BLUEs](./Readings/C2M2L2-The%20Kalman_Filter-Bias_Blues.pdf)

- [Reading - Lesson 2 Supplementary Reading: The Kalman Filter - The Bias BLUEs](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/ShQXz/lesson-2-supplementary-reading-the-kalman-filter-the-bias-blues)

## The Nonlinear Kalman Filter

- [Video - Lesson 3: Going Nonlinear - The Extended Kalman Filter](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/qIyk3/lesson-3-going-nonlinear-the-extended-kalman-filter)

- [Reading - Lesson 3: Going Nonlinear - The Extended Kalman Filter](./Readings/C2M2L3-The_Extended_Kalman_Filter.pdf)

- [Reading - Lesson 3 Supplementary Reading: Going Nonlinear - The Extended Kalman Filter](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/bPC90/lesson-3-supplementary-reading-going-nonlinear-the-extended-kalman-filter)

- [Video - Lesson 4: An Improved EKF - The Error State Extended Kalman Filter](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/7Nwfw/lesson-4-an-improved-ekf-the-error-state-extended-kalman-filter)

- [Reading - Lesson 4: An Improved EKF - The Error State Extended Kalman Filter](./Readings/C2M2L4-An_Improved_EKF.pdf)

- [Reading - Lesson 4 Supplementary Reading: An Improved EKF - The Error State Kalman FIlter](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/701Yo/lesson-4-supplementary-reading-an-improved-ekf-the-error-state-kalman-filter)

- [Video - Lesson 5: Limitations of the EKF](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/OCrZc/lesson-5-limitations-of-the-ekf)

- [Reading - Lesson 5: Limitations of the EKF](./Readings/C2M2L5-Limitations_of_the_EKF.pdf)

- [Video - Lesson 6: An Alternative to the EKF - The Unscented Kalman Filter](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/voRRb/lesson-6-an-alternative-to-the-ekf-the-unscented-kalman-filter)

- [Reading - Lesson 6: An Alternative to the EKF - The Unscented Kalman Filter](./Readings/C2M2L6-An_alternative_to_the_EKF.pdf)

- [Reading - Lesson 6 Supplementary Reading: An Alternative to the EKF - The Unscented Kalman Filter](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/0GuWv/lesson-6-supplementary-reading-an-alternative-to-the-ekf-the-unscented-kalman)

## Weekly Assignment

- [Lab - Module 2 Graded Notebook: Estimating a Vehicle Trajectory](./Labs/assg_learner.ipynb)