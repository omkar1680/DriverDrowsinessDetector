# DriverDrowsinessDetector
This project is a Python script that identifies the alertness state of a vehicle operator and notifies upon crossing critical threshold.

Landmark Features: computer vision, facial landmark detection, customisable audio alerts.

Libraries Used:
cv2 (OpenCV) for video capture and image processing.
dlib for facial landmark detection.
numpy for mathematical operations.
pygame for playing audio alerts when drowsiness is detected.

Functionality:
Captures real-time video from the webcam using OpenCV.
Detects facial landmarks using dlib’s shape_predictor_68_face_landmarks.dat.
Computes eye aspect ratio to detect if the user is blinking, drowsy, or active.
Plays an alert sound if drowsiness is detected.
