---
layout: post
title: "SlidePin: A DTW-Based Unlocking System"
featured-img: slidepin
---

The main purpose of this work is to use machine learning algorithms to improve the security and accuracy of smartphone sliding unlocking.

## Background 

Using users historic slide path in smartphone to build a unlocking model. To identify whether it is an attacker when user unlock the screen, the system will compare the new input slide path with the above model. In this project, first we record slide information (coordinate, velocity, acceleration, etc) for training,and do some filter to the path waveform. Then, we use DTW reform the uncertain length waveform into the same length. Finally, base on different ML-algorithm such as LR,SVM,DNN, we built different model. Next time, when user slide on the screen to unlock smart phones, we will compare the new path with above model.

Unlike the traditional slide unlocking mode, in this project, even if attacker slide a right password path, the system still need to compare other information above.

## Responsibilities

I responsible for most development and algorithm work.


## Demonstrate

![](/images/slidepin/p1.jpg)

![](/images/slidepin/p2.png)




