Real-time Finger Counting using OpenCV and MediaPipe
This project implements a real-time finger detection and counting system using OpenCV and MediaPipe's hand tracking framework. The system captures video input from a webcam, detects the hand, and counts the number of extended fingers, even in complex backgrounds or when the face is visible in the frame.

Features
Detects and tracks a hand in real time.
Counts the number of fingers that are extended.
Works even when the face is in the frame.
Uses MediaPipe's hand tracking for stable and accurate detection.
Easy to run with Python and OpenCV.
How It Works
Hand Detection: MediaPipe is used to detect hand landmarks in real time from a webcam feed.
Finger Counting: The system identifies the position of the fingers and checks if they are extended or folded based on the relative position of key landmarks.
Real-time Output: The number of extended fingers is displayed on the video feed.
