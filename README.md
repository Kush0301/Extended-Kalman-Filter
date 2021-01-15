# Localization Algorithms

## Extended Kalman Filter

### Description

The task at hand was to recursively estimate the state of a mobile platform given the position of the landmarks in the robot's frame of reference at every instant. The vehicle was equipped with a 2D LiDAR sensor and velocity inputs (translational and rotational) were given to the platform. Data association was assumed. The initial pose of the robot as well as the noise with respect to the input and sensor model was known.

### Ground Truth
<p float="left">
  <img src="gtruth.png" width="300" />
  <img src="gtruth2.png" width="300" /> 
</p>


### Results 
<p float="left">
  <img src="ekf.gif" width="300" />
  <img src="ekf1.gif" width="300" /> 
</p>

