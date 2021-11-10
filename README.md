# Driver Drowsiness Detection using Convolutional Neural Networks 😴 🚫 🚗
Drowsiness detection is a safety technology that can prevent accidents that are caused by drivers who fell asleep while driving.

# Applications 🎯
This can be used by riders who tend to drive for a longer period of time that may lead to accidents

# Code Requirements 🦄
The example code is in Python (version 2.7 or higher will work).

# Dependencies🔱
import cv2
import keras
import pygame
import numpy

# Description 📌
A computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy.

# Problem Domain✔️
This project falls on the concepts of Convolutional Neural Networks and deep learning. Here by utilizing facial landmarks which are detected by the camera are passed to a Convolutional Neural Network (CNN) to classify drowsiness. The proposed CNN based model can be used to build a real-time driver drowsiness detection system for embedded systems and Android devices with high accuracy and ease of use. To detect the face and extract the eye region from the face images, face detection algorithm is used in this work. A multilayer convolution neural network is developed to extract features from dynamically identified key frames from camera sequences and used for learning phase. A SoftMax layer in CNN classifier is used to classify the driver as sleep or non-sleep. This system alerts driver with an alarm when the driver is in sleepy mood and helps in preventing accidents. 

# Proposed Architecture🏛️
![image](https://user-images.githubusercontent.com/76680213/141062388-b938fce9-f8e0-4223-85fe-29b947e9355f.png)

# Execution 🐉
To run the code, type python drowsiness detection.py

Model link: https://drive.google.com/file/d/1xgb4Nke5aeOUQXbCydYPg6WyJdrNcOrH/view?usp=sharing

NOTE: This Model is a part of the running process. As space is a constraint here, it is uplaoded in the drive.
