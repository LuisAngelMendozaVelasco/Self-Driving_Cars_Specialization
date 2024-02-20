# Module 2: Visual Features - Detection, Description and Matching

Visual features are used to track motion through an environment and to recognize places in a map. This module describes how features can be detected and tracked through a sequence of images and fused with other sources for localization as described in Course 2. Feature extraction is also fundamental to object detection and semantic segmentation in deep networks, and this module introduces some of the feature detection methods employed in that context as well.

## Learning Objectives

- Apply feature detection methods to driving images
- Distinguish between different feature detectors and descriptors
- Match image features using brute-force matching
- Perform improved image feature matching with maximum likelihood and KLT
- Formulate and solve visual odometry for a self-driving car dataset
- Improve VO performance through outlier rejection

## Image Features and Feature Detectors

- [Video - Lesson 1: Introduction to Image features and Feature Detectors](https://www.coursera.org/learn/visual-perception-self-driving-cars/lecture/V7iCJ/lesson-1-introduction-to-image-features-and-feature-detectors)

- [Reading - Lesson 1: Introduction to Image features and Feature Detectors](./Readings/C3M2L1-Image_Features.pdf)

- [Video - Lesson 2: Feature Descriptors](https://www.coursera.org/learn/visual-perception-self-driving-cars/lecture/CYWEj/lesson-2-feature-descriptors)

- [Reading - Lesson 2: Feature Descriptors](./Readings/C3M2L2-Image_Feature_Descriptors.pdf)

- [Reading - Supplementary Reading: Feature Detectors and Descriptors](https://www.coursera.org/learn/visual-perception-self-driving-cars/supplement/NLMlA/supplementary-reading-feature-detectors-and-descriptors)

- [Video - Lesson 3 Part 1: Feature Matching](https://www.coursera.org/learn/visual-perception-self-driving-cars/lecture/YLRTR/lesson-3-part-1-feature-matching)

- [Reading - Lesson 3 Part 1: Feature Matching](./Readings/C3M2L3P1-Feature_Matching.pdf)

- [Reading - Supplementary Reading: Feature Matching](https://docs.opencv.org/4.0.0/dc/dc3/tutorial_py_matcher.html)

- [Video - Lesson 3 Part 2: Feature Matching: Handling Ambiguity in Matching](https://www.coursera.org/learn/visual-perception-self-driving-cars/lecture/6W0lx/lesson-3-part-2-feature-matching-handling-ambiguity-in-matching)

- [Reading - Lesson 3 Part 2: Feature Matching: Handling Ambiguity in Matching](./Readings/C3M2L3P2-Feature_Matching-Handling_Ambiguity_in_Matching.pdf)

- [Reading - Supplementary Reading: Feature Matching](https://docs.opencv.org/4.0.0/d1/de0/tutorial_py_feature_homography.html)

## Outlier Rejection & Visual Odometry

- [Video - Lesson 4: Outlier Rejection](https://www.coursera.org/learn/visual-perception-self-driving-cars/lecture/hQpYK/lesson-4-outlier-rejection)

- [Reading - Lesson 4: Outlier Rejection](./Readings/C3M2L4-Outlier_Rejection.pdf)

- [Reading - Supplementary Reading: Outlier Rejection](https://cdn.preterhuman.net/texts/science_and_technology/artificial_intelligence/Computer%20Vision%20A%20Modern%20Approach%20-%20Forsyth%20,%20Ponce.pdf)

- [Video - Lesson 5: Visual Odometry](https://www.coursera.org/learn/visual-perception-self-driving-cars/lecture/Zq8NO/lesson-5-visual-odometry)

- [Reading - Lesson 5: Visual Odometry](./Readings/C3M2L5-Visual_Odometry.pdf)

- [Reading - Supplementary Reading: Visual Odometry](https://www.coursera.org/learn/visual-perception-self-driving-cars/supplement/bGK1j/supplementary-reading-visual-odometry)

## Weekly Assignment: Visual Odometry for Localization in Autonomous Driving

- [Lab - Visual Odometry for Localization in Autonomous Driving](./Labs/Visual%20Odometry%20for%20Localization%20in%20Autonomous%20Driving.ipynb)