# **Finding Lane Lines on the Road** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

<img src="examples/laneLines_thirdPass.jpg" width="480" alt="Combined Image" />

Overview
---

When we drive, we use our eyes to decide where to go.  The lines on the road that show us where the lanes are act as our constant reference for where to steer the vehicle.  Naturally, one of the first things we would like to do in developing a self-driving car is to automatically detect lane lines using an algorithm.

In this project we detect lane lines in images using Python and OpenCV.

## Requirements
---
- Anaconda with Python 3 (Which internally includes all the other requirements)
- jupyter


## Setup
---
```
- git clone https://github.com/Mohit-Ak/CarND-LaneLines-P1.git
- cd CarND-LaneLines-P1
#### For CPU
- conda env create -f environment.yml
#### For GPU
- source activate carnd-term1
- jupyter notebook Lane_Detection_Project.ipynb

```

## Sample Output Images
---
### solidWhiteCurve
![solidWhiteCurve](test_images_output/solidWhiteCurve.png)

### solidWhiteRight
![solidWhiteRight](test_images_output/solidWhiteRight.jpg)

### solidYellowCurve
![solidYellowCurve](test_images_output/solidYellowCurve.jpg)

### solidYellowCurve2
![solidYellowCurve2](test_images_output/solidYellowCurve2.jpg)

### solidYellowLeft
![solidYellowLeft](test_images_output/solidYellowLeft.jpg)

### whiteCarLaneSwitch
![whiteCarLaneSwitch](test_images_output/whiteCarLaneSwitch.jpg)

