---
layout: post
author: Ian Robinson
title: "Post #3"
date: 2022-09-16 14:15:00 -0400
---
Tripoli Post #3

This week I ahve been navigating on how to fix the timing and how the tooltip displays whenever the mouse hovers over the index of the file on the peakcentre line plot. so far i ahave been able to get a tool tip to display showing the index of the postion the red dot is located on the graph. The tool tip is working half of the time displaying the index when i move the cursor sometimes it disappeaers and sometimes it does not. I have been looking through Squid code and researching on the internet to find the best solution to fix the timing of the tooltips showing and hiding. I have learned looking through Squid code and online it is much easier to do this if it is an actual node on the fxml page instead of trying to base it on the x and y cordinates where the cursor is located on the page or in my case a specific part of a page where a line plot is located.

Adding the tooltip to the beamshape line plot in the beamshape controller class will be easier beacuse there will be less factors to worry about so it might be good for me to take care of that first before I finish implementing all the funtions in the peakcentre line plot.