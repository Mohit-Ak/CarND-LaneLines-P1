# **Finding Lane Lines on the Road** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

Overview
---
 The lines on the road act as our constant reference for where to steer the vehicle.  The aim of this project is to develop a self-driving car autmatic lane detection system using Python and OpenCV. A pipeline processing is applied to a series of individual images and ultimately to a video stream.

## Expected Output
<img src="examples/laneLines_thirdPass.jpg" width="480" alt="Combined Image" />


## Requirements

- Anaconda with Python 3 (Which internally includes all the other requirements)
- jupyter


## Setup

```
- git clone https://github.com/Mohit-Ak/CarND-LaneLines-P1.git
- cd CarND-LaneLines-P1
- For CPU
- conda env create -f environment.yml
- For GPU
- source activate carnd-term1
- jupyter notebook Lane_Detection_Project.ipynb

```
## Pipeline
![pipeline_image](pipeline_image.png)


## Sample Output Images
---
The test images are located under - test_images
### solidWhiteCurve
![solidWhiteCurve](test_images_output/solidWhiteCurve.jpg)

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

## Sample Videos
---
Test Videos are located under - test_videos
Test Videos output are located under - test_videos_output

## Conclusion

