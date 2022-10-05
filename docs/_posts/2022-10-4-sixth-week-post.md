---
layout: post
author: Ian Robinson
title: "Post #6"
date: 2022-10-04 14:15:00 -0400
---
Tripoli Post #6

This week, I am getting started on implementing some of the ideas to get the tooltip feature to function correctly within the Tripoli app. I have been doing assignments and exams in the other classes that I am currently taking while researching and developing a part of the Tripoli software. I was first able to get a basic idea of how to interact with the canvas displaying the tooltip where I want with the data I supplied after doing some research. this link [javafx canvas](https://stackoverflow.com/questions/53740820/how-do-i-add-a-tooltip-to-a-rectangular-region-of-a-javafx-canvas) helped me understand how to add the tooltip with canvases. I added this in PeakCentreLinePlot.java lines 200-220, displaying the tooltip with the correct index according to the cursor's x position on the canvas.

But I have been spending a lot of time researching the best way to add the smaller graphs as a popup on the peak centre line plot . I do not believe the tooltip can display an actual node/canvas when showing the tooltip, so looking for another option to display the smaller graphs where I want is what I am focusing on at the moment. I should be able to implement the tooltip for the beam shape line plot without having to worry about displaying another canvas. 