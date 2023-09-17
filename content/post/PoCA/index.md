---
title: Portable Communications Array
description: A journey exploring RF, 3D Printing, and countless obstacles
slug: poca
date: 2023-06-09 00:00:00+0000
image: cover.jpg
categories:
    - Projects
tags:
    - RF
    - Electrical Engineering
    - Troubleshooting
---
## Introduction
This project began when I received a Raspberry Pi 4b as a gift from my lovely girlfriend. I had long sought a similarly capable single-board computer to host a [Safing Community Node](https://safing.io/spn/). After realizing the (many) risks of hosting a public node from my dorm internet, I began researching other uses. After stumbling upon the [Raspberry Pi Recovery Kit](https://www.doscher.com/work-recovery-kit/) by Jay Doscher, I had an idea to adapt his design into a mobile Software Defined Radio (SDR)/digital storage device.

### Disclaimer
I know that this is far from the most efficient configuration for a RPi-based SDR. I chose this specific route not simply based on efficacy but rather as a way to explore other engineering challenges besides RF.

This article was written with assumption that you have *some* knowledge of Raspberry Pi computing and RF.

### Desired Specifications
* SDR capable of TX and RX
* 6 hour battery life
* 1 TB of storage
* Ability to run as a storage server
* Ability to run [SDR++](https://www.sdrpp.org/) locally
* Watertight when closed
* Ability to fit all necessary peripherals inside watertight case
* Portable

## 3D Modeling
Since the majority of the 3D models were generously provided by  Jay Doscher, I only needed to slightly modify the I/O plate and the overall dimensions to fit my purposes. Since my changes were minor, I primarily used [Tinkercad](https://tinkercad.com/) to design the models. I used the 3D printing resources at the [Billodue Makerspace](https://www.instagram.com/p/CqoHByoPkVG/?img_index=1) to FDM print all the parts over the course of two weeks.

![Revised keyboard tray](rotate.gif)

I returned to the makerspace regularly for a couple months as I prototyped and experimented with the design. After a few iterations. It's important to note that I forgot to post-process my parts, so if you intend to follow this blog as a guide I would recommend you follow one of the many guides online to properly prepare your parts.

## Part Selection
Finding and ordering the parts was very time consuming. The complexity of the 
