# Self-Driving Car Project 4. Advanced Lane Finding

## Project Overview

In this project, our goal is to write a software pipeline to identify the lane boundaries in a video. The goals/steps of this project are the following:

* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images
* Apply a distortion correction to raw images
* Use color transforms, gradients, etc., to create a thresholded binary image
* Apply a perspective transform to rectify binary image ("birds-eye view")
* Detect lane pixels and fit to find the lane boundary
* Determine the curvature of the lane and vehicle position with respect to center
* Warp the detected lane boundaries back onto the original image
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position

The images for camera calibration are stored in the folder called `camera_cal`.  The images in `test_images` are for testing our pipeline on single frames.  If we want to extract more test images from the videos, we can simply use an image writing method like `cv2.imwrite()`, i.e., we can read the video in frame by frame as usual, and for frames we want to save for later we can write to an image file.  

The examples of the output from each stage of our pipeline are saved in the folder called `output_images`. The video called `project_video.mp4` is the video our pipeline will work well on.  
