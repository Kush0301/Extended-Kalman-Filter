# Localization Algorithms

## Extended Kalman Filter

### Description

The task at hand was to recursively estimate the state and the 2D Trajectory of a mobile platform given the position of the landmarks in the robot's frame of reference at every instant. The vehicle was equipped with a 2D LiDAR sensor and velocity inputs (translational and rotational) were given to the platform. Data association was assumed. The initial pose of the robot as well as the noise with respect to the input and sensor model was known.

### Ground Truth
<p float="left">
  <img src="results/gtruth.png" width="300" />
  <img src="results/gtruth2.png" width="300" /> 
</p>


### Results 
<p float="left">
  <img src="results/ekf.gif" width="300" />
  <img src="results/ekf1.gif" width="300" /> 
</p>


## Error-State Extended Kalman Filter

### Description

The objective was to estimate the state and the 3D trajectory of a platform using an Error-State Extended Kalman Filter. The filter relied on IMU data as the control inputs for the prediction step. For the correction step, GPS and 3D LiDAR updates were available. The sensor readings were collected from the CARLA Simulator.


### Results

<p float="left">
  <img src="results/Ekf_3d.gif" width="400" />
</p>

