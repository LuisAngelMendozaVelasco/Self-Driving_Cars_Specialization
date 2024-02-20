# Module 0: Welcome to Course 2: State Estimation and Localization for Self-Driving Cars

This module introduces you to the main concepts discussed in the course and presents the layout of the course. The module describes and motivates the problems of state estimation and localization for self-driving cars. An accurate estimate of the vehicle state and its position on the road is required at all times to drive safely.

## Learning Objectives

- Understand the problem of state estimation and its relationship to vehicle localization
- Review the types of sensors introduced througout the course
- Review the main project offered in this course

## Introduction to State Estimation and Localization for Self-Driving Cars

- [Video - Welcome to the Self-Driving Cars Specialization!](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/ZL5rP/welcome-to-the-self-driving-cars-specialization)

- [Video - Welcome to the Course](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/7vWF2/welcome-to-the-course)

- [Reading - Course Prerequisites: Knowledge, Hardware & Software](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/pAvW4/course-prerequisites-knowledge-hardware-software)

- [Reading - How to Use Discussion Forums](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/gaip6/how-to-use-discussion-forums)

- [Reading - How to Use Supplementary Readings in This Course](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/jtvGD/how-to-use-supplementary-readings-in-this-course)

## Meet the Self-Driving Car Experts

- [Video - Meet the Instructor, Jonathan Kelly](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/NlSF0/meet-the-instructor-jonathan-kelly)

- [Video - Meet the Instructor, Steven Waslander](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/IZJtT/meet-the-instructor-steven-waslander)

- [Video - Meet Diana, Firmware Engineer](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/rhkgF/meet-diana-firmware-engineer)

- [Video - Meet Winston, Software Engineer](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/yk9r6/meet-winston-software-engineer)

- [Video - Meet Andy, Autonomous Systems Architect](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/DhPz5/meet-andy-autonomous-systems-architect)

- [Video - Meet Paul Newman, Founder, Oxbotica & Professor at University of Oxford](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/O7wNl/meet-paul-newman-founder-oxbotica-professor-at-university-of-oxford)

- [Video - The Importance of State Estimation](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/6SKF2/the-importance-of-state-estimation)

---

# Module 1: Least Squares

The method of least squares, developed by Carl Friedrich Gauss in 1795, is a well known technique for estimating parameter values from data. This module provides a review of least squares, for the cases of unweighted and weighted observations. There is a deep connection between least squares and maximum likelihood estimators (when the observations are considered to be Gaussian random variables) and this connection is established and explained. Finally, the module develops a technique to transform the traditional 'batch' least squares estimator to a recursive form, suitable for online, real-time estimation applications.

## Learning Objectives

- Understand the squared error optimization criterion and its use
- Explain how least squares is employed in parameter estimation problems
- Apply the unweighted and weighted least squares methods to parameter estimation
- Apply a recursive version of least squares to update parameter estimates as new measurements arrive
- Explain how Jacobian matrices are used

## Least Squares

- [Video - Lesson 1 (Part 1): Squared Error Criterion and the Method of Least Squares](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/zDFtr/lesson-1-part-1-squared-error-criterion-and-the-method-of-least-squares)

- [Reading - Lesson 1 (Part 1): Squared Error Criterion and the Method of Least Squares](./Readings/C2M1L1P1-The_Squared_Error_Criterion_and_the_Method_of_Least_Squares.pdf)

- [Video - Lesson 1 (Part 2): Squared Error Criterion and the Method of Least Squares](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/Ewy9K/lesson-1-part-2-squared-error-criterion-and-the-method-of-least-squares)

- [Reading - Lesson 1 (Part 2): Squared Error Criterion and the Method of Least Squares](./Readings/C2M1L1P2-Weighted_Least_Squares.pdf)

- [Reading - Lesson 1 Supplementary Reading: The Squared Error Criterion and the Method of Least Squares](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/NeMMR/lesson-1-supplementary-reading-the-squared-error-criterion-and-the-method-of)

- [Lab - Lesson 1 Practice Notebook: Least Squares](./Labs/C2M1L1.ipynb)

## Recursive Least Squares

- [Video - Lesson 2: Recursive Least Squares](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/0UbTb/lesson-2-recursive-least-squares)

- [Reading - Lesson 2: Recursive Least Squares](./Readings/C2M1L2-Recursive_Least_Squares.pdfs)

- [Lab - Lesson 2 Practice Notebook: Recursive Least Squares](./Labs/C2M1L2.ipynb)

- [Reading - Lesson 2 Supplementary Reading: Recursive Least Squares](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/DFzb7/lesson-2-supplementary-reading-recursive-least-squares)

- [Video - Lesson 3: Least Squares and the Method of Maximum Likelihood](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/lecture/XcOb7/lesson-3-least-squares-and-the-method-of-maximum-likelihood)

- [Reading - Lesson 3: Least Squares and the Method of Maximum Likelihood](./Readings/C2M1L3-Least_Squares_and_Maximum_Likelihood.pdf)

- [Reading - Lesson 3 Supplementary Reading: Least Squares and the Method of Maximum Likelihood](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/supplement/grtUG/lesson-3-supplementary-reading-least-squares-and-the-method-of-maximum)