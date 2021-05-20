---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: e15-3yp-Fire-Detection-and-Alert-System
title: Fire Detection and Alert System
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Fire Detection and Alert System

---

## Team
-  E/15/154, JAYASOORIYA J.K.C.N., [e15154@eng.pdn.ac.lk](mailto:e15154@eng.pdn.ac.lk)
-  E/15/187, KULANJITH G.D., [devingallage@gmail.com](mailto:devingallage@gmail.com)
-  E/15/142, JAYALATH A.H.G.D., [ganindudananja@gmail.com](mailto:ganindudananja@gmail.com)

## Table of Contents
1. [Introduction](#introduction)
2. [Solution Architecture](#solution-architecture )
3. [Links](#links)

---

## Introduction

According to National Fire Protection Association (NFPA), there were 1,319,500 fire cases were reported only in USA in 2017. Nearly 40% of them are structure fires. Moreover, following statements are highlights from NFPA report.

- In 2017, 22 fires in the United States resulted in losses of at least $10 million each, for a cumulative total of $12.5 billion in direct property losses. These fires resulted in the deaths of 52 civilians and one firefighter, and injuries to 213 civilians and 20 firefighters.
- The other 20 large-loss fires in 2017 involved structures and resulted in a total property loss of $747.7 million.
- Smoking materials were the leading cause of home fire deaths in 2012-2016.  

![Graph](docs/data/images/)  

[Intro](docs/data/videos/)




## Solution Architecture

There are two ways a fire can be happened.

- Sudden fire

- Slowly growing fire

We are going to implement a set of devices with the capability of detecting smoke and CO particles so that, the device will detect both the above mentioned fire types and the users will get warnings only if neccessary through an alarm on the device itself and an alert will be sent to the users of the mobile app and the web application. If the fire is massive or danger enough the intensity of the alarm will get increased and if the option for emergency is enabled, the emergency authorities will get notifications about the fire disaster.

How the device works?

- There are two types of devices come with Ignio and they are “Ignio node” and the “Ignio relay”. The Ignio node is integrated with the sensors and an alarm so that it takes data from sensors and pass down to the Ignio relay through wi-fi which is connected to the ISP directly via a home network or an enterprise network. The sudden fires will get detected by the Ignio node itself through the sensors by detecting the passing of particular bandwidths for particle density and CO emission rate. And, the other type of fires will be predicted by analysing the periodic data on the microservice architectured API.


## Links

- <a href = "https://github.com/cepdnaclk/e15-3yp-Fire-Detection-and-Alert-System" target = "_blank"> Project Repository </a>
- <a href = "https://cepdnaclk.github.io/e15-3yp-Fire-Detection-and-Alert-System/" target = "_blank">Project Page</a>
- <a href = "http://www.ce.pdn.ac.lk/" target = "_blank">Department of Computer Engineering</a>
- <a href = "https://eng.pdn.ac.lk/" target = "_blank">University of Peradeniya</a>


[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
