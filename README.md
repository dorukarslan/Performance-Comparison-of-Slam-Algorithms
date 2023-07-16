# Performance-Comparison-of-Slam-Algorithms
This repository houses the complete research and analysis of various SLAM algorithms, the datasets used, and the results. The primary aim is to offer an exhaustive comparative study of SLAM algorithms in different environments, focusing on two main aspects - the execution speeds and the accuracy of the algorithms.  

![slamev](https://github.com/dorukarslan/Performance-Comparison-of-Slam-Algorithms/assets/79598598/5884827b-4c8c-4a1f-a3fc-85e4bf2c0c99)

## Abstract

Simultaneous localization and mapping (SLAM) algorithms have revolutionized various fields, most notably robotics, thanks to rapid advancements in computer science. While these algorithms hold immense potential, their performance largely depends on the nature of the environment and the data source.

This research primarily focuses on comparing the performance of various SLAM algorithms in different environments. To achieve this, we've created multiple datasets by integrating test videos shot in varied environmental conditions with sensor data. Following this, we executed the SLAM algorithms against these datasets and compared their results.

The key factors considered during the comparison are:

• Execution Speed  
• Accuracy of the algorithms  
All the results were visualized for a clear understanding of the algorithm behaviors based on tested conditions.

# Introduction

SLAM algorithms have carved a niche in today's technologically-driven world, where rapid mapping and environmental understanding are imperative. These algorithms offer the potential for autonomous devices such as UAVs and robots to map any desired region quickly.

Two primary approaches to SLAM algorithms are LIDAR and VSLAM. Both approaches have their pros and cons, and their effectiveness depends on environmental conditions. It's important to remember that the performance of SLAM algorithms is closely tied to the environment where they operate. Factors like weather conditions, light intensity, different objects, and the quality of data source play crucial roles in determining the accuracy of the results.

The algorithms used in this study are:

• ORB-SLAM  
• Direct Sparse Odometry with Loop Closure(LDSO)  

![ldsoand](https://github.com/dorukarslan/Performance-Comparison-of-Slam-Algorithms/assets/79598598/1507d27a-365e-4865-a5b7-e14da65f285b)

# Acknowledgments


It's worth noting that each approach may have advantages and disadvantages in different environments and conditions, and therefore, we analyzed the performance of both approaches under various test conditions.

The reliability of SLAM algorithm output depends on the environment in which the process takes place. Therefore, we tested the algorithms under different conditions, taking into account weather conditions, light intensity, and different objects in the environment, using existing datasets with various difficulty levels. It's important to consider the testing conditions and choose the right dataset to yield relevant results.

To facilitate the comparison, we used the EuRoC MAV dataset, which contains sequences of stereo images, synchronized IMU measurements, and ground truth poses for each sequence. We created a repository that splits the images into frames and combines them with the sensor data using the Androsensor application to make the dataset easier to use. You can find the dataset creation repository at 
[dorukarslan/EuRoC_Generator](https://github.com/dorukarslan/EuRoC_Generator)

# Sample Comparison

![ldsoERG](https://github.com/dorukarslan/Performance-Comparison-of-Slam-Algorithms/assets/79598598/3fc5a169-0c83-47a9-b4b1-e746288565b6)


![slamERG](https://github.com/dorukarslan/Performance-Comparison-of-Slam-Algorithms/assets/79598598/fb28704b-721e-4ebe-aadf-5012cfab474a)

