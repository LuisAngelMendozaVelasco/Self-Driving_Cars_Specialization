# Module 2: Mapping for Planning

The occupancy grid is a discretization of space into fixed-sized cells, each of which contains a probability that it is occupied. It is a basic data structure used throughout robotics and an alternative to storing full point clouds. This module introduces the occupancy grid and reviews the space and computation requirements of the data structure. In many cases, a 2D occupancy grid is sufficient; learners will examine ways to efficiently compress and filter 3D LIDAR scans to form 2D maps.

## Learning Objectives

- Create an occupancy grid map to identify static obstacles in the environment.
- Apply the log odds update to efficiently update occupancy beliefs.
- Apply filtering and compression to map 3D lidar scans to 2D occupancy grids.
- Understand the impact of dynamic obstacles on occupancy grids.

## Mapping for Planning

- [Video - Lesson 1: Occupancy Grids](https://www.coursera.org/learn/motion-planning-self-driving-cars/lecture/oJcwU/lesson-1-occupancy-grids)

- [Reading - Lesson 1: Occupancy Grids](./Readings/C4M2L1-Occupancy_Grids.pdf)

- [Video - Lesson 2: Populating Occupancy Grids from LIDAR Scan Data (Part 1)](https://www.coursera.org/learn/motion-planning-self-driving-cars/lecture/p4Na5/lesson-2-populating-occupancy-grids-from-lidar-scan-data-part-1)

- [Reading - Lesson 2: Populating Occupancy Grids from LIDAR Scan Data (Part 1)](./Readings/C4M2L2P1-Populating_Occupancy_Grids_from_LIDAR_Scan_Data.pdf)

- [Video - Lesson 2: Populating Occupancy Grids from LIDAR Scan Data (Part 2)](https://www.coursera.org/learn/motion-planning-self-driving-cars/lecture/VcH67/lesson-2-populating-occupancy-grids-from-lidar-scan-data-part-2)

- [Reading - Lesson 2: Populating Occupancy Grids from LIDAR Scan Data (Part 2)](./Readings/C4M2L2P2-Populating_Occupancy_Grids_from_LIDAR_Scan_Data.pdf)

- [Video - Lesson 3: Occupancy Grid Updates for Self-Driving Cars](https://www.coursera.org/learn/motion-planning-self-driving-cars/lecture/MxKWO/lesson-3-occupancy-grid-updates-for-self-driving-cars)

- [Reading - Lesson 3: Occupancy Grid Updates for Self-Driving Cars](./Readings/C4M2L3-Occupancy_Grid_Updates_for_Autonomous_Driving.pdf)

- [Video - Lesson 4: High Definition Road Maps](https://www.coursera.org/learn/motion-planning-self-driving-cars/lecture/bB5Dx/lesson-4-high-definition-road-maps)

- [Reading - Lesson 4: High Definition Road Maps](./Readings/C4M2L4-Lanelet_Map.pdf)

- [Reading - Module 2 Supplementary Reading](https://www.coursera.org/learn/motion-planning-self-driving-cars/supplement/q7I1T/module-2-supplementary-reading)

## Module 2 Weekly Assignment: Occupancy Grid Generation

- [Lab - Occupancy Grid Generation](./Labs/Module%202%20Assessment.ipynb)