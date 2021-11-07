# Sensor_Fusion_for_IMU_Orientation_Estimation
This repository contains MATLAB codes and sample data for sensor fusion algorithms (Kalman and Complementary Filters) for 3D orientation estimation using Inertial Measurement Units (IMU).

Data included in this online repository was part of an experimental study performed at the University of Alberta (by Milad Nazarahari (nazaraha@ualberta.ca) as a part of the Ph.D. thesis under the supervision of Dr. Hossein Rouhani (hrouhani@ualberta.ca)).

User Manual: Please see the file named “User Manual” for details of the codes, datasets, and the related references.

License: file named “License”.

Data Files: files named “DataLong.mat”, “DataShort.mat”, and “SFA_Gains.mat”.

Sensor Fusion Algorithm: file named “SensorFusionAlgorithms.zip” contains the MATLAB files of the all tested sensor fusion algorithms.

Main File:

 file named “SensorFusion_Assessment.m”. Execute this script to evaluate various sensor fusion algorithms (you must have all the required files in the current directory to execute this code).

“SFA_Performance.m”: will present the error in estimated orientation by sensor fusion algorithm.

Optimization of Sensor Fusion Algorithms: 

file named “Optimization.m”. Execute this script to find the optimal parameters for a sensor fusion algorithm. You need to create a function for the sensor fusion that you want to find its optimal parameters. Two examples are:

“Opt_Madgwick2011_MIMU.m”: find the optimal parameters for Madgwick 2011.

“Opt_Nazarahari2020.m”: find the optimal parameters for Nazarahari 2020.

Utility functions:

“QuaternionProduct.m”: performs quaternion product.

“QuaternionConjugate.m”: calculates quaternion conjugate.

“Quat2EulerAngles.m”: converts quaternions to Euler angles.

“avg_quaternion_markley.m”: calculates average of quaternions.

“FiltFilt3D.m”: performs 3D low-pass filtering.


