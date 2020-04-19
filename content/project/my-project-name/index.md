---
title: "Autonomouse UAV"
date: 2020-04-18T17:06:16-07:00
draft: false
---
These projects demonstrated main tasks for IMAV 2016 competition.
All of these algorithms are written based on the OpenCV library with constrained on real-time process on UP-bored embedded system. Obviously, at first, an Optical Flow algorithm is used for robot position controlling. According to our goal, the sparse Optical flow algorithm implemented instead of its dense algorithm because of its low latency. At the end of the round, the robot had to land on a moving platform covered up with an H-shape marker. In this step we got in trouble with two main problems the first one is that cause detection of black and white color in HSV color model is intrinsically difficult and the other one is robot shadows mirrored on the marker. A few approaches had been implemented and in the best result, at the first step, the outer black-border detected and then in it we searched for three rectangles which are perpendicular together. The third step as you see in video show is the detection of a 1*1 dimensional window as the entrance to a building. In this case, the Blue color of the window border helps a lot in detecting this part. The robot can set its location on the x-y axes by minimizing the error between the center of the image and the center of the window detected by the algorithm. In the last session, you see an ORB-SLAM is used to track the previous wave points which set for the algorithm.

[This is video]{{< youtube https://www.youtube.com/watch?v=1TxTkjjMrmw >}}
