# Real-Time Face Recognition Attendance System

This project is a Python-based system that uses facial recognition to mark attendance in real-time using a webcam feed. It is useful for classrooms, offices, and secure entry points where automation and accuracy are important.

## Features

- Real-time face detection and recognition using Dlib and OpenCV
- Automatic attendance marking with in-time and out-time tracking
- Face data registration system
- Attendance logs stored in CSV and SQLite database
- Spoof detection to prevent misuse (e.g., using photos)
- Multi-face tracking using centroid-based re-identification

## Technologies Used

- Python 3.x
- OpenCV
- Dlib
- SQLite
- face_recognition (Dlib-based 128D embeddings)
- Tkinter or Flask (for GUI or web interface)
