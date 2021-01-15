# Localization Algorithms

## Extended Kalman Filter

### Description

The task at hand was to recursively estimate the state of a mobile platform given the position of the landmarks in the robot's frame of reference at every instant. The vehicle was equipped with a 2D LiDAR sensor and velocity inputs (translational and rotational) were given to the platform. Data association was assumed. The initial pose of the robot as well as the noise with respect to the input and sensor model was known.

### Ground Truth

<p align="left">
<img width="400" height="300" src="https://github.com/Kush0301/Extended-Kalman-Filter/blob/master/gtruth.png?raw=true">
</p>
<p align="left">
<img width="400" height="300" src="https://github.com/Kush0301/Extended-Kalman-Filter/blob/master/gtruth2.png?raw=true">
</p>

### Results 

<p align="left">
<img width="400" height="300" src="https://github.com/Kush0301/Extended-Kalman-Filter/blob/master/ekf.gif?raw=true">
</p>

<p align="right">
<img width="400" height="300" src="https://github.com/Kush0301/Extended-Kalman-Filter/blob/master/ekf1.gif?raw=true">
</p>

