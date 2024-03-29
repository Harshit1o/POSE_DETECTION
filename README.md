# POSE_DETECTION
Sit-Up Counter using MediaPipe and OpenCV
Overview

This Python program utilizes the MediaPipe library along with OpenCV to count sit-ups in real-time using a webcam feed. It detects the landmarks of the human body, specifically focusing on the hip, knee, and ankle joints to determine the angle between them, which helps identify the sitting-up and lying-down stages of a sit-up exercise.
Requirements

    ```Python 3.x
    OpenCV
    MediaPipe```

## Installation

Clone or download the repository to your local machine.
Install the required dependencies using pip:

    ```pip install opencv-python mediapipe```

## Usage

Connect your webcam or built-in camera to your computer.
Run the Python script situp_counter.py.

  ```python situp_counter.py```

A live webcam feed will open up displaying the video stream with overlays indicating the detected landmarks and the current sit-up count.
Perform sit-up exercises within the camera's view.
The program will count the number of sit-ups completed based on the predefined angle thresholds between the hip, knee, and ankle joints.
To exit the program, press 'q' on your keyboard.

## Customization

You can adjust the angle thresholds for detecting sit-up stages (down and up) by modifying the angle values in the Python script.
Feel free to customize the visualization, such as changing the colors or adding additional information overlays, to suit your preferences.
You can also add many poses at a time and make it an application.
Happy Coding!

## Acknowledgments

This project utilizes the MediaPipe library developed by Google Research, which provides pre-trained models for pose estimation.
Special thanks to the OpenCV community for their contributions to computer vision.

# Thank You!
