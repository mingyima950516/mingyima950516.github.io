---
layout: post
title: "Factory Employee Identification and Alerting System"
featured-img: factory
---


## Background 

This project was developed for a factory in Suzhou China. The computer vision algorithm in this project is similar to the project "Customer Statistics and Identification System". But this project focus on early warning and employee movement route statistics. The system identifies the employees who should not enter a certain area. And record and analyze each employee's daily movement path in the factory.

In this system, multiple cameras in the factory push video streams to the central server with GPU. Then the service will analyze the video frame. By combine detection and tracker, we can distinguish each single object. After that the face recognition algorithm will generate face-id vector. Currently we are planning to improve the system with Re-ID technology. The purpose is to improve the recall rate of early warning.

## Responsibilities

I responsible for all development and algorithm work.


## Demonstrate

![](/images/factory/p1.png)

![](/images/factory/p2.png)

![](/images/factory/p3.png)

![](/images/factory/p4.png)

![](/images/factory/p5.png)




