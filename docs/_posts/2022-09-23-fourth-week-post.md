---
layout: post
author: Ian Robinson
title: "Post #4"
date: 2022-09-23 14:15:00 -0400
---
Tripoli Post #4

This week I am still working on the issue of the Tooltip feature that needs to be added to the peak centre line plot and the beam shape line plot of the peak shapes portion of Tripoli. In lines 200 - 215 of PeakCentreLinePlot.java, I have been trying to set up the tooltip based on the x position of the current canvas the cursor is on. It seems that it loads the correct position and the tooltip appears on the canvas but the tooltip does not disappear after moving the cursor to another position. I was thinking of possibly adding a few variables  indicating my previous position. Then when changed, the tooltip would disappear afterward. Also, after a meeting with Dr. Bowring he gave me the idea of creating new canvases and adding them to the canvas already there considering I have to add the thumbnail plots to the tooltip anyways. I feel like I have a better idea of how to complete the tooltip feature for the peak centre line plot.

The beam shape line plot will be much easier to implement because there are only 2 points on the line plot that is of interest at the moment that needs to be viewed. Of course, that may change down the road but for now, it will do.