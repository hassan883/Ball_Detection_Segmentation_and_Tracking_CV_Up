# Ball_Detection_Segmentation_and_Tracking_CV_Up

This repository contains implementations of various computer vision techniques focusing on ball detection, segmentation, feature extraction, and tracking. These tasks are essential components in applications such as sports analytics, interactive games, and robotic vision systems.

## Overview

The repository is divided into several key sections:
1. **Image Segmentation and Detection** - Techniques to identify and segment ball objects using conventional computer vision methods.
2. **Feature Calculation** - Extracting shape and texture features from segmented ball images.
3. **Object Tracking** - Implementing a Kalman filter to track the motion of a ball based on noisy observations.

## Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-image

## Tasks and Implementation

### Task 1: Image Segmentation and Detection
Automated segmentation using Gaussian blurring, edge detection, and contour extraction. 

![Ground Truth Output](https://github.com/hassan883/Ball_Detection_Segmentation_and_Tracking_CV_Up/blob/main/frame-54.png)
![Segmentation Output](https://github.com/hassan883/Ball_Detection_Segmentation_and_Tracking_CV_Up/blob/main/frame-54_GT.png)

### Task 2: Feature Calculation
Calculation and visualization of shape and texture features for different ball types.

![Feature Visualization](https://github.com/hassan883/Ball_Detection_Segmentation_and_Tracking_CV_Up/blob/main/Picture1.png)

### Task 3: Object Tracking
Using a Kalman filter for tracking the trajectory of a moving ball.

![Tracking Visualization](https://github.com/hassan883/Ball_Detection_Segmentation_and_Tracking_CV_Up/blob/main/frame-54_masked.png)

## Results
The repository includes evaluation metrics such as Dice Similarity Score for segmentation accuracy and RMSE for tracking precision.

## Getting Started
Instructions for setting up the project locally:



## Contributors
- [Hassan Javed](https://github.com/hassan883)

## License
This project is licensed under the MIT License 


