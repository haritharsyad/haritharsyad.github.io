---
layout: post
title: "Moving Average and Standard Deviation for Temperature Sensor"
description: "My team design and synthesize an IC layout for calculating moving average and standard deviation for a temperature sensor"
date: 2022-12-05
feature_image: images/TempSensor.png
final_report: files/Final_Report.pdf
tags: [tips, work]
---

For my digital VLSI course final project, we designed an IC using Verilog then synthesized and optimized it using Genus and Innovus. The goal of our circuit is to be able to calculate the moving average and standard deviation from the last 14 readings of a temperature sensor and letting the user choose which ones they want at the output. We made two different designs for this project; One where its the barebones design and one where we used techniques such as pipelining and clock gating to further optimize it.

<!--more-->

## Responsibility

In this project, I wrote the Verilog codes for the two designs as well as synthesized it using Genus to get the timing, area, and power reports so we can find the one that performs the best. I also wrote the testbench for our design and we tested it on 30 and 100 different inputs from the temperature sensor to make sure that our circuit is consistent and accurate. I learned a lot doing this project like prototyping a circuit from the problem statement, different register types we could use, making flexible testbench code that we can easily customize, and the synthesis process from Genus and Innovus.

## Challenges

One of the biggest challenges we came across in this project is figuring out how to make the calculations as accurate as possible. This primarily came from having to use division when calculating the output so we had to rearrange our equations so that we only use one division module. We also had to find a way to make circuit able to round to the nearest integer.

With our time constraints we also had to learn how to streamline our process from Verilog to a completed IC layout which taught us a lot about using Genus and Innovus.
