---
layout: post
title: "LM-MS Micro-Services Framework"
featured-img: lmms
---
Lightweight & multi-language micro-services framework (LM-MS) 

A multi-language, lightweight, high-performance micro-services framework, users only need to care about application logic coding,without having to think about fault-tolerance, service load balance, etc.

## Background 

This project is based on java, Hprose and mqtt. The micro-services system is consist of "Main Control Service(MCS)" , "api-gate" , "APP-service(AS)".

 **i)** Due to the need to provide multiple backend services to the previous project such as video streaming, face-id database synchronization, receiving customer shopping data, admin management system, customer statistics data, etc. The logic is complex, so the backend provides data support in the form of micro-services. 

 **ii)** Project backend code was written by multiple languages (java and php), and current mainstream frameworks rarely support multilingual. 

 **iii)** Current popular micro-services framework is complex in configuration and need a lot of resources. 
 
 **iV)** Using traditional http is less efficient, and there are more tasks in the system that require multiple backend services, resulting in a large loss of resources. 

Github：<https://github.com/ashjpo/LM-MS>

(A more detail description is in github.)

## Responsibilities

I responsible for all development work.


## Demonstrate

![](/images/ms/p2.png)

![](/images/ms/p1.jpg)





