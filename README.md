# HINNet_Dataset

Datasets of 'HINNet: Inertial Navigation for Head-Mounted sensors using a Neural Network' paper.

Each hdf5 file contains 6 types of data:

### • IMU Data
Collected by a XSens Dot on the head.
### 1. acc
Acceleration.
### 2. gyro
Gyroscope data.
### 3. xstime
Time stamp.

### • Groundtruth Data
Collected by an application based on Visual Inertial Odometry (VIO) in a phone.
#### 1. pos
Position.
#### 2. ori
Orientation.
#### 3. artime
Time stamp.


Datasets have already been cleaned and synchronised.
