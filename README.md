# Pan Card Tempering Detector

## Table of Content
* [Overview](#overview)
* [Motivation](#motivation)
* [Problem Solving steps](#Problem Solving steps)


## Overview
In this project, we detect tampering of Pan card using computer vision.<br>
<img src="sample_data/842391.png">

## Motivation
This project will help different organisations in detecting whether the ID that is the pan card provided to them by their employees or customers is original or fake.

## Problem Solving steps
1. Get Images from user
2. Check for size and for mat of the image
3. Chane the shape and size of image according to the original image
4. Convert the image to grayscale
5. Find the similarity index of the images
6. Find the threshold of the image
7. Find the contour and grab those contour using `IMUTILS`
8. Draw a bounding rectangle using these contours
9. Plot difference, threshold, original and tampered image
10. Compare all the images and check the similaritiy score to decide tampering.
