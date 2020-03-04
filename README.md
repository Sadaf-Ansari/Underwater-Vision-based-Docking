# Underwater Vision-based-Docking

Author: Sadaf Ansari
Created: 3 March 2020

Underwater vision-based docking for AUVs is a two step procedure:
1. Marker Detection
2. Visual-servoing

For vision-based docking of Autonomous Underwater Vehicles (AUVs), I am using ArUco Markers and the ArUco OpenCV Library.

The link nto the ArUco OpenCV documentation:
https://docs.opencv.org/trunk/d5/dae/tutorial_aruco_detection.html

Vision-based Detection of ArUco Markers can be in two ways:
1. Single Marker Detection (for prelimianry tests);
2. Simultaneous detection of two ArUco Markers will increase the docking accuracy of the AUV.

Visual-servoing will take tyhe AUV towards the Docking Station (DS). It moves vehicle using four thruster outputs (T1, T2, T3, T4) received from Image data.



