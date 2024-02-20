# Module 4: Vehicle Dynamic Modeling

The first task for automating an driverless vehicle is to define a model for how the vehicle moves given steering, throttle and brake commands. This module progresses through a sequence of increasing fidelity physics-based models that are used to design vehicle controllers and motion planners that adhere to the limits of vehicle capabilities.

## Learning Objectives

- Develop a kinematic bicycle model of a car with velocity and steering angle inputs
- Develop a dynamic bicycle models of a car with velocity and steering angle inputs
- Differentiate between models of tire forces
- Develop a model for actuation in a car, from pedal and steering wheel to tire forces

## Dynamic Modeling

- [Video - Lesson 1: Kinematic Modeling in 2D](https://www.coursera.org/learn/intro-self-driving-cars/lecture/pScZH/lesson-1-kinematic-modeling-in-2d)

- [Reading - Lesson 1: Kinematic Modeling in 2D](./Readings/C1M4L1-Kinematic_Modeling_in_2D.pdf)

- [Reading - Supplementary Readings for Module 4](https://d3c33hcgiwev3.cloudfront.net/csKJTCDXEemj-RKX93anOA_72d8f77020d711e9ace9b31057616ac0_Models-of-Mobile-Robots-in-the-Plane.pdf?Expires=1708560000&Signature=WpGvhKP8cv8tj57PPjWlXl8~A1Z-0zeIrDMJgmOYxhiI1GWnGR-pD7r11h9LgQZO7DEYhftNEaBXMFc3dppgU6OyNBvmLVyhwvVUzC7~gcThZM9XOV6a3dzNEv8Mf7meypDtln7BKd9TPIMChyhpkp4U~XngqUgGEtTWoJeQC5s_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

- [Video - Lesson 2: The Kinematic Bicycle Model](https://www.coursera.org/learn/intro-self-driving-cars/lecture/Bi8yE/lesson-2-the-kinematic-bicycle-model)

- [Reading - Lesson 2: The Kinematic Bicycle Model](./Readings/C1M4L2-The_Kinematic_Bicycle_Model.pdf)

- [Reading - Lesson 2 Supplementary Reading: The Kinematic Bicycle Model](https://d3c33hcgiwev3.cloudfront.net/vjVDuyDXEemj-RKX93anOA_be4b8ab020d711e9a1134155eeec67a0_Lateral-Vehicle-Dynamics.pdf?Expires=1708560000&Signature=Ibbtby~RNINMpZBDUrhaiPH1UiqQCT1pCHMDLyPC-gJvziyaMrEuv-7vo3lHxP~TtVWo~zDqSgmMLbf7L7tkhmUQWXVKFtXuzxr6WNBAjWkqx4RX4~Qj1zsD25GzWKpcUJQM5ImqN7cNWXDDxkenHJl1tBHld7boa4z57XaItyQ_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

- [Video - Lesson 3: Dynamic Modeling in 2D](https://www.coursera.org/learn/intro-self-driving-cars/lecture/yNa0v/lesson-3-dynamic-modeling-in-2d)

- [Reading - Lesson 3: Dynamic Modeling in 2D](./Readings/C1M4L3-Dynamic_Modeling_in_2D.pdf)

- [Reading - Lesson 3 Supplementary Reading: Dynamic Modeling in 3D](https://www.coursera.org/learn/intro-self-driving-cars/supplement/MJaIo/lesson-3-supplementary-reading-dynamic-modeling-in-3d)

- [Video - Lesson 4: Longitudinal Vehicle Modeling](https://www.coursera.org/learn/intro-self-driving-cars/lecture/V8htX/lesson-4-longitudinal-vehicle-modeling)

- [Reading - Lesson 4: Longitudinal Vehicle Modeling](./Readings/C1M4L4-Longitudinal_Vehicle_Model.pdf)

- [Reading - Lesson 4 Supplementary Reading: Longitudinal Vehicle Modeling](https://ftp.idu.ac.id/wp-content/uploads/ebook/tdg/TERRAMECHANICS%20AND%20MOBILITY/epdf.pub_vehicle-dynamics-and-control-2nd-edition.pdf)

- [Video - Lesson 5: Lateral Dynamics of Bicycle Model](https://www.coursera.org/learn/intro-self-driving-cars/lecture/1Opvo/lesson-5-lateral-dynamics-of-bicycle-model)

- [Reading - Lesson 5: Lateral Dynamics of Bicycle Model](./Readings/C1M4L5-Lateral_Dynamic_Vehicle_Model.pdf)

- [Reading - Lesson 5 Supplementary Reading: Lateral Dynamics of Bicycle](https://d3c33hcgiwev3.cloudfront.net/vjVDuyDXEemj-RKX93anOA_be4b8ab020d711e9a1134155eeec67a0_Lateral-Vehicle-Dynamics.pdf?Expires=1708560000&Signature=Ibbtby~RNINMpZBDUrhaiPH1UiqQCT1pCHMDLyPC-gJvziyaMrEuv-7vo3lHxP~TtVWo~zDqSgmMLbf7L7tkhmUQWXVKFtXuzxr6WNBAjWkqx4RX4~Qj1zsD25GzWKpcUJQM5ImqN7cNWXDDxkenHJl1tBHld7boa4z57XaItyQ_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

- [Video - Lesson 6: Vehicle Actuation](https://www.coursera.org/learn/intro-self-driving-cars/lecture/fSAQG/lesson-6-vehicle-actuation)

- [Reading - Lesson 6: Vehicle Actuation](./Readings/C1M4L6-Vehicle_Actuation.pdf)

- [Reading - Lesson 6 Supplementary Reading: Vehicle Actuation](https://www.coursera.org/learn/intro-self-driving-cars/supplement/wml6X/lesson-6-supplementary-reading-vehicle-actuation)

- [Video - Lesson 7: Tire Slip and Modeling](https://www.coursera.org/learn/intro-self-driving-cars/lecture/iSRpt/lesson-7-tire-slip-and-modeling)

- [Reading - Lesson 7: Tire Slip and Modeling](./Readings/C1M4L7-Tire_Slip_and_Modeling.pdf)

- [Reading - Lesson 7 Supplementary Reading: Tire Slip and Modeling](https://d3c33hcgiwev3.cloudfront.net/Sbj8KCDaEem9HA6xGGaRfg_49fb831020da11e99167b944be537fd0_Tire-model.pdf?Expires=1708560000&Signature=i3jd8l8Uz6m0YvmmnVrEYL1Ieg611pThHkaMk4oIpOIXTOfIc-LOaxe41RSeyNtqxO9oGlutBK6mqE8GduqrIrUauD2AXtDQIhspuULdJBhjdwBy0cJV-AhYqOpxa-ZPiDXPd5TK2DaBeJ1PcVE1FRK~a4V9mK6h08V2KGNFbm0_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

## Learn from Industry Experts

- [Video - Challenges for the Industry](https://www.coursera.org/learn/intro-self-driving-cars/lecture/BBJF6/challenges-for-the-industry)

## Weekly Assignment

- [Lab - Module 4 Programming Exercise: Kinematic Bicycle Model](./Labs/Kinematic_Bicycle_Model.ipynb)

- [Lab - Module 4 Programming Exercise: Longitudinal Vehicle Model](./Labs/Longitudinal_Vehicle_Model.ipynb)