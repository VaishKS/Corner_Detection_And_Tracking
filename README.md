# Corner Detection And Tracking

## About

This repository implements custom Harris corner detector and uses it to track corners over time with patch templates and with SIFT descriptors on the first 200 frames of the popular KITTI Visual Odometry dataset.

## Design

The program consists of two classes: Class Image and Class Matcher. The Image class encapsulates all the methods related to an image and the Matcher class encapsulated all the methods required to match 2 images.

## Result with custom descriptors

<div align="center">
<p>
<img src="output/custom_corner_tracking_patch.gif" width="400"/>
</p>
<br>
</div>

## Result with SIFT descriptors

<div align="center">
<p>
<img src="output/custom_corner_tracking_patch.gif" width="400"/>
</p>
<br>
</div>
