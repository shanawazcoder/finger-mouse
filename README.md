Finger Mouse

Finger Mouse is a lightweight Python project that lets you control your computer cursor using hand movements captured by your webcam. It uses MediaPipe to track your index finger for movement and a simple thumb–index pinch gesture for clicking. No extra hardware is required — only a webcam and Python.

Features

Move your mouse cursor with your index finger

Click by bringing your thumb close to your index finger

Works in real time

Simple codebase and easy to modify

Uses common libraries: OpenCV, MediaPipe, PyAutoGUI

Requirements

Python 3.7+

Webcam

Libraries:

pip install opencv-python mediapipe pyautogui

How It Works

MediaPipe detects your hand and identifies key landmarks

The index finger tip controls cursor position

When the thumb comes close to the index finger, a left-click is triggered

Movements are smoothed with a threshold to avoid jitter

Usage

Clone the repository:

git clone https://github.com/yourusername/finger-mouse.git


Run the script:

python finger_mouse.py


Keep your hand in front of the webcam and move your index finger to guide the cursor.

File Overview

finger_mouse.py – Main script containing hand-tracking and mouse-control logic

Notes

Works best in good lighting

Keep your hand in the center of the camera frame

For faster response, close other applications while running the script

License

This project is released under the MIT License.
