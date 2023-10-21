# Face Detection and Recognition Project

Welcome to our Face Detection and Recognition project, where we harness the power of Python, OpenCV, and the face_recognition library to create a real-time facial recognition system. Dive into the world of computer vision and machine learning as we guide you through the setup and execution of this fascinating application.

## Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [How It Works](#how-it-works)
5. [Dependencies](#dependencies)
6. [Acknowledgements](#acknowledgements)
7. [Support and Contribution](#support-and-contribution)

## Introduction
This repository is dedicated to the implementation of a real-time face detection and recognition system using the renowned OpenCV library and the highly accurate face_recognition library. Our script seamlessly captures video from your default camera, identifies faces frame by frame, and recognizes individuals from a set of pre-loaded images.

## Prerequisites
Before embarking on this visual journey, ensure that your machine is equipped with:
- Python 3.x
- A working camera

## Installation
To set the stage for our facial recognition adventure, install the required libraries using pip:

```bash
pip install opencv-python face_recognition numpy
```
## How It Works
- Video Capture: The script captures video from your default camera, creating a live feed.
- Face Encoding: We preload images of known individuals (Barack Obama and Joe Biden in this example) and encode their facial features.
- Real-Time Recognition: As the video plays, the script detects faces in each frame and attempts to match them with the pre-encoded faces.
- Annotations: Recognized faces are highlighted with bounding boxes, and their names are displayed on the screen.
Interactive Exit: Press 'q' on your keyboard at any time to gracefully exit the application.

## Dependencies
- OpenCV: For video capture and rendering.
- face_recognition: For efficient and accurate face detection and recognition.
- numpy: For numerical computations and data handling.

## Acknowledgements
This project stands on the shoulders of giants, utilizing the face_recognition library, which is built atop dlib, a modern toolkit containing a plethora of machine learning algorithms.

## Support and Contribution
Feel inspired? Have questions? Open an issue or submit a pull request. Your journey through the realms of computer vision and machine learning starts here!


