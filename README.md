# Gesture Recognition

Problem statement: Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.
The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

Thumbs up:  Increase the volume
Thumbs down: Decrease the volume
Left swipe: 'Jump' backwards 10 seconds
Right swipe: 'Jump' forward 10 seconds  
Stop: Pause the movie

## Table of Contents
* Objectives
* Problem solving methodology: General Approach
* Model building and observations


## General Information
The training data consists of a few hundred videos categorised into one of the five classes. 
Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). 
These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use. 


## Technologies Used
- numpy - version 1.20.3
- pandas - version 1.3.4
- seaborn - version 0.11.2

**conclusion:**

Different accuracy has been achieved on modules like 
Model 8:
validation accuracy:78%
Training accuracy:86%

Model 10:
validation accuracy:86%
Training accuracy:86%

Model 19:
validation accuracy:97%
Training accuracy:99%

## Contact
Assignment submitted by Yogesh Kolhe and Anand Shah.
https://github.com/yoyoyogesh/Gesture-Recognition-case-study.git feel free to contact us!
