---
layout: post
author: Ian Robinson
title: "Post #1"
date: 2022-09-01 14:15:00 -0400
---
Tripoli Post #1

This week I worked on refining peak shapes display, functions, and documentation of Tripoli. I worked on making peak shapes auto-select the first file from the resources on startup. While working on it,
I realized there were a few conflicts with the service not running the task on the file selected on startup, causing it not to produce the beam shape and G-beam graph. So instead, I did the process without the peak service. Also, I worked on implementing forward and backward key selection in choosing files and displaying the peak shapes. I learned a little more about JavaFX and its EventHandlers and listeners on how to press keys to affect the program. I also learned a bit about GraphicContext and how to remove and add new markings to a canvas after it was already rendered. This was due to implementing adding marks on a graph when a file was chosen from the list of resources.