# Micromouse Maze Solver (Using A-Star Algorithm)

This repository contains the code developed for a micromouse maze solving system. The system takes an input of a maze map using a camera and this image is converted into a grid which in turn determines find the shortest path between the proposed points.

# Requirements
1) Python3
2) OpenCV
3) HeapQ
4) MatPlotlib

# Steps
## 1) Input image fed to the system using camera:

![IMAG2747](https://user-images.githubusercontent.com/24778913/54785699-e84b8680-4c4c-11e9-99d3-8a50f430c43f.jpg)
<br>
<br>
## 2) Detection of the industrial maze using image thresholding:

![Screenshot from 2019-03-22 02-23-11](https://user-images.githubusercontent.com/24778913/54785762-07e2af00-4c4d-11e9-8472-08152d4930b1.png)
<br>
<br>
## 3) Conversion of the input image into a smaller grid (for size optimization):

![Screenshot from 2019-03-22 02-28-13](https://user-images.githubusercontent.com/24778913/54787244-22b72280-4c51-11e9-83b4-04e8021a5ee3.png)
<br>
<br>
## 4) Input for the start and the end point(s) from the end user:

![Screenshot from 2019-03-22 02-28-53](https://user-images.githubusercontent.com/24778913/54785826-33659980-4c4d-11e9-9c9f-c7e87fa48fb7.png)
<br>
<br>
## 5) Solution of the micromouse grid using A-Star Algorithm:
The sources that were useful for the design of the algorithmic code have been provided in the 'References' section in document below.<br>
![Screenshot from 2019-03-22 02-29-04](https://user-images.githubusercontent.com/24778913/54785841-3f515b80-4c4d-11e9-87f1-57d7b7badad7.png)
<br>
<br>

# Upcoming Target Improvements:
1) The process of conversion of a high resolution image into a grid is not accurate and efficient. The process to improve the accuracy and efficiency with a different approach is in progress.<br>
2) Plotting of the result on the live camera feed is not currently implemented. The process to do the same is being worked upon.<br>


# References:
1)<a href="https://www.youtube.com/watch?v=ySN5Wnu88nE&t=199s">Computerphile</a><br>
2)<a href="https://www.youtube.com/watch?v=aKYlikFAV4k">CodingTrain</a><br>
3)<a href="https://medium.com/@nicholas.w.swift/easy-a-star-pathfinding-7e6689c7f7b2">Medium</a><br>
4)<a href="https://www.raywenderlich.com/3016-introduction-to-a-pathfinding">raywenderlich</a><br>
5)<a href="https://www.analytics-link.com/single-post/2018/09/14/Applying-the-A-Path-Finding-Algorithm-in-Python-Part-1-2D-square-grid">Analytics link</a>
