# Module 5: Vehicle Longitudinal Control

Longitudinal control of an autonomous vehicle involves tracking a speed profile along a fixed path, and can be achieved with reasonable accuracy using classic control techniques. This week, you will learn how to develop a baseline controller that is applicable for a significant subset of driving conditions, which include most non-evasive or highly-dynamic motions.

## Learning Objectives

- Design a PID controller for a linear system
- Decompose a coupled nonlinear vehicle model and extract a linear decoupled longitudinal model
- Develop a feedforward controller for longitudinal vehicle control

## Proportional-Integral-Derivative (PID)

- [Video - Lesson 1: Proportional-Integral-Derivative (PID) Control](https://www.coursera.org/learn/intro-self-driving-cars/lecture/QMOMH/lesson-1-proportional-integral-derivative-pid-control)

- [Reading - Lesson 1: Proportional-Integral-Derivative (PID) Control](./Readings/C1M5L1-PID_Control.pdf)

- [Reading - Lesson 1 Supplementary Reading: Proportional-Integral-Derivative (PID) Control](https://www.coursera.org/learn/intro-self-driving-cars/supplement/PXljB/lesson-1-supplementary-reading-proportional-integral-derivative-pid-control)

- [Video - Lesson 2: Longitudinal Speed Control with PID](https://www.coursera.org/learn/intro-self-driving-cars/lecture/6qs1g/lesson-2-longitudinal-speed-control-with-pid)

- [Reading - Lesson 2: Longitudinal Speed Control with PID](./Readings/C1M5L2-Longitudinal_Speed_Control_with_PID.pdf)

- [Reading - Lesson 2 Supplementary Reading: Longitudinal Speed Control with PID](https://ftp.idu.ac.id/wp-content/uploads/ebook/tdg/TERRAMECHANICS%20AND%20MOBILITY/epdf.pub_vehicle-dynamics-and-control-2nd-edition.pdf)

- [Video - Lesson 3: Feedforward Speed Control](https://www.coursera.org/learn/intro-self-driving-cars/lecture/bj4Xw/lesson-3-feedforward-speed-control)

- [Reading - Lesson 3: Feedforward Speed Control](./Readings/C1M5L3-Feedforward_Speed_Control.pdf)

- [Reading - Lesson 3 Supplementary Reading: Feedforward Speed Control](https://d3c33hcgiwev3.cloudfront.net/fdEeaiDvEem3Cw5hhdQCGg_7e168b3020ef11e99a25a9f602841cc7_Feedforward-speed-control.pdf?Expires=1708560000&Signature=bFNFAHPGtagAPaPtqUKiDtULVgVKL~HB5S7CiOHSEi5D4CgMAnzXzUMK7QBofXbCK9MfwxfUgUVpp75qQnjqLyZ1sDExLS3-1BbZEpuvQdA-uFUsA5SDgwAsyYcnaxePS~8tNQL9t~JBLDS38JMHsJ65Y-n9aqArDjfro0PEivU_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

## Learn from Industry Experts

- [Video - Zoox's Approach to Self-Driving Cars](https://www.coursera.org/learn/intro-self-driving-cars/lecture/mjGku/zooxs-approach-to-self-driving-cars)