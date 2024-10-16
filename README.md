# DriverDrowsinessDetector
Overview:

This project implements a real-time drowsiness detection system using computer vision and facial landmark detection. The system captures video input, tracks eye movements, and alerts the user if signs of drowsiness are detected. This project can be particularly useful in scenarios like driver fatigue monitoring or other alertness detection systems.

Features:

Real-time Video Processing: Captures video from a webcam and processes frames to detect facial landmarks.
Eye Blink Detection: Calculates the Eye Aspect Ratio (EAR) to determine blinking patterns.
Drowsiness Alerts: Plays an audio alert when drowsiness or extended eye closure is detected.
Customizable: Replace the alert sound with any audio file of your choice.
Technologies Used
Python 3.x
OpenCV for video capture and frame processing.
dlib for detecting facial landmarks.
NumPy for numerical computations.
pygame for playing audio alerts.
