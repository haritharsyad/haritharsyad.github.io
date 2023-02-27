---
layout: post
title: "Home Security System"
description: "We build a Home Security System based around the ATMEGA328p chip"
date: 2022-01-01
feature_image: images/home-security.jpg
final_report: files/Home-Security-Report.pdf
tags: [tips, work]
---
In this project, me and my teammate build a Home Security System based around the ATMEGA328p chip used in an Arduino. Our system can switch between two modes; a home security mode and a lie detector mode. In the home security mode, we activate the laser, water, and shock sensors which will trigger if there is someone who walks in front of it, a water probe that triggers if there is flooding, and a shock sensor that triggers in situations like an earthquake. In the lie detector mode, we can detect if someone is lying through their galvanic skin response and we can manually shock someone if they are lying.

<!--more-->

## Responsibility

In this project, I coded the Arduino sketch in C++ for the home security mode as well as implemented the mode switching mechanism. I also made the schematic of our circuit in KiCAD and made all the component placements in our PCB design while my teammate worked on the routing for the components. I learned a lot from this project especially in the design process of a circuit through to the final prototype of our design in a two layer PCB. This is one of my favorite projects and it inspired me to make more DIY projects at home using the Arduino and inspired to explore other microcontrollers such as the ESP32 for more functionality in my projects. I find it to be a very practical test of all the concepts I've learned through my undergrad courses and allowed me be creative in what I can come up with and challenge me to make my crazy ideas come to life.
