# Open-CV-projects-
Building a Hand Tracking System using OpenCV
download
Share
crown iconSyed Abdul Gaffar Shakhadri — Published On July 8, 2021 and Last Modified On July 15th, 2021
Advanced Computer Vision Image Image Analysis Libraries Project Python Unstructured Data

This article was published as a part of the Data Science Blogathon

OpenCV is a library used for computer vision applications. With help of OpenCV, we can build an enormous number of applications that work better in real-time. Mainly it is used for image and video processing.

More information about OpenCV can be acquired here (https://opencv.org/)

Along with OpenCV, we are going to use the MediaPipe library.

 

MediaPipe
MediaPipe is a framework mainly used for building audio, video, or any time series data. With the help of the MediaPipe framework, we can build very impressive pipelines for different media processing functions.

Some of the major applications of MediaPipe.

Multi-hand Tracking
Face Detection
Object Detection and Tracking
Objectron: 3D Object Detection and Tracking
AutoFlip: Automatic video cropping pipeline etc.
Hand Landmark Model
Hand Tracking landmark model
Source: https://google.github.io/mediapipe/solutions/hands.html
Basically, the MediaPipe uses a single-shot palm detection model and once that is done it performs precise key point localization of 21 3D palm coordinates in the detected hand region.

The MediaPipe pipeline utilizes multiple models like, a palm detection model that returns an oriented hand bounding box from the full image. The cropped image region is fed to a hand landmark model defined by the palm detector and returns high-fidelity 3D hand key points.

Now let us implement the Hand tracking model.

Install the required modules

–> pip install opencv-python

–> pip install mediapipe
