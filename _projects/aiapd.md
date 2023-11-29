---
layout: page
title: AI Assisted Powerpoint Designer
description: Sketch-recognition solutions to assist creating presentations
img: /assets/img/powerpoint.png
importance: 4
category: academic
---

Intelligent user interfaces aim to give the most convenience and expressive power to the user. In this project, we worked on creating a sketch-recognition based solutions to designing presentations. I was responsible for creating an interface between PowerPoint Office.js API and our recognition library and extending the python-pptx library to include additional .pptx modification functionalities. I also took part in training SVM's with selected features for basic shape recognitions. 

This project was particulary difficult because of the very limited functionality Office API provides. For PowerPoint, Office API only provided the ability to access current presentation file. Therefore, we needed to figure out a way of extracting necessary information from the file and manipulate it instantly when the user prompts. I surveyed the user requirements and designed an efficient architecture for this complex task. In Figure 1, you can see a test of our software from earlier versions.
