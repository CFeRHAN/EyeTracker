# Eye Tracker

An eye tracking application implemented in Python using the OpenCV library.

## Project Description

This project aims to track the movement of an eye in a video stream. It uses computer vision techniques and image processing algorithms to detect and track the eye region in each frame of the video.

## Features

- Detects and tracks the eye region in real-time video.
- Displays the thresholded image and the region of interest (ROI) with eye detection and tracking.
- Allows the user to manually select the ROI frame that contains the eye itself.

## How to Run the Eye Tracker

1. Make sure you have Python and OpenCV installed on your system.
2. Clone this repository to your local machine.
3. Navigate to the project directory.

```shell
$ cd eye-tracker


Run the following command to start the eye tracker:
$ python eye_tracker.py

In the video window, click and drag to select the region of interest (ROI) frame that contains the eye.
The eye tracking process will start, and you will see the thresholded image and the ROI frame with eye detection and tracking.
Press the "Esc" key to exit the application.

Requirements:
Python
OpenCV

File Structure:
eye_tracker.py: The main Python script that runs the eye tracking application.
eye_recording.flv: Sample video file for eye tracking.
README.md: This file providing information about the project.
Graphics/: Folder containing graphical assets used in the project.

Acknowledgments
The eye tracking application is based on computer vision techniques and image processing algorithms implemented using the OpenCV library.