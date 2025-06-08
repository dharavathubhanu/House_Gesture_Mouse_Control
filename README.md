# Hand Gesture-Based Mouse Control using OpenCV and MediaPipe
This Python project allows you to control your mouse cursor movement and clicking actions using just your hand gestures captured through a webcam. It uses MediaPipe for real-time hand tracking and PyAutoGUI for cursor control.

# Features
Move the mouse cursor using your index finger.

Automatically click when the index finger tip and thumb tip come close.

Real-time hand tracking and gesture interaction.

Works on any computer with a webcam and Python installed.

# How it works

How It Works
Uses OpenCV to capture video from the webcam.

MediaPipe detects 21 hand landmarks.

Index finger tip (id=8) controls cursor movement.

Thumb tip (id=4) is used to detect a "click" gesture.

If the vertical distance between thumb and index finger is less than 40 pixels, a mouse click is triggered.

# Dependencies

python mouse_click.py


