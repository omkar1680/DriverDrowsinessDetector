# DriverDrowsinessDetector
Facial Landmark Detector File: https://github.com/italojs/facial-landmarks-recognition/blob/master/shape_predictor_68_face_landmarks.dat

Overview:

This project implements a real-time drowsiness detection system using computer vision and facial landmark detection. The system captures video input, tracks eye movements, and alerts the user if signs of drowsiness are detected. This project can be particularly useful in scenarios like driver fatigue monitoring or other alertness detection systems.

Features:

Real-time Video Processing: Captures video from a webcam and processes frames to detect facial landmarks.
Eye Blink Detection: Calculates the Eye Aspect Ratio (EAR) to determine blinking patterns.
Drowsiness Alerts: Plays an audio alert when drowsiness or extended eye closure is detected.
Customizable: Replace the alert sound with any audio file of your choice.


Technologies Used:

Python 3.x
OpenCV for video capture and frame processing.
dlib for detecting facial landmarks.
NumPy for numerical computations.
pygame for playing audio alerts.


Usage:

The system will start capturing video from your webcam.
It will track your face and monitor eye blinks.
If prolonged eye closure is detected (a sign of drowsiness), an audio alert will be played to notify you.

Customization:

You can replace the default alert sound by replacing the "beep1.mp3" file in the code with your own audio file.


Future Improvements:

Face tracking under low-light conditions.
Improved accuracy for different facial structures.
Support for multiple alert types (visual, haptic feedback).


Contact:

For questions or contributions, feel free to contact me at theonlyone1680@gmail.com
