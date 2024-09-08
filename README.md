
# Face Detection Live Using OpenCV

## Problem Statement

With the rise of video conferencing, surveillance, and various facial recognition applications, the ability to detect faces in real-time has become increasingly important. This project aims to develop a live face detection system using a webcam. The objective is to detect human faces in real-time from the webcam feed and visualize the results using bounding boxes.

## Objective

The primary goal of this project is to:

- Capture video in real-time from the default webcam on the user's machine.
- Process each frame to detect human faces using a pre-trained model.
- Draw bounding boxes around detected faces and display the processed video.
- Exit the process gracefully when prompted by the user.

## Features

- Real-time video feed from webcam.
- Conversion of the video frames to grayscale for faster processing.
- Application of a pre-trained Haar Cascade classifier to detect faces in real-time.
- Display of bounding boxes around detected faces in the video stream.


## Setup Instructions

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd Face_Detection_Live_Using_opencv
   ```

3. Install required Python packages:
   ```bash
   pip install opencv-python
   ```

4. Run the project:
   As mentioned in the code

## Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- Webcam

## Conclusion

This project demonstrates how to leverage OpenCV's pre-trained Haar Cascade classifier to perform real-time face detection from a live video feed. It can be used as a base for more complex face detection and recognition tasks in applications like video conferencing, security systems, and user authentication.
