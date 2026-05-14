Attendance Management System

A real-time Face Recognition Based Attendance Management System developed using Python, OpenCV, and Machine Learning techniques to automate attendance marking through webcam-based face detection and recognition.

📌 Project Overview

Traditional attendance systems are time-consuming, error-prone, and vulnerable to proxy attendance. This project provides a contactless and automated attendance solution using face recognition technology.

The system detects and recognizes faces from a live webcam feed and automatically marks attendance in an Excel sheet with timestamps.

🚀 Features
Real-time face detection using webcam
Face recognition using pre-trained face encodings
Automatic attendance marking
Multiple face detection support
Excel/CSV attendance report generation
User-friendly interface with Start/Stop controls
Reduced proxy attendance and manual errors
Lightweight and efficient system


🛠️ Technologies Used
Python
OpenCV
NumPy
dlib
face_recognition
Pandas
OpenPyXL
Flask (optional for dashboard integration)


Attendance-Management-System/
│
├── dataset/                 # Stored face images
├── attendance/              # Generated attendance sheets
├── models/                  # Trained face encodings/models
├── static/                  # CSS, JS, assets
├── templates/               # HTML templates
├── app.py                   # Main application file
├── train_model.py           # Face encoding/training script
├── requirements.txt         # Required dependencies
└── README.md



⚙️ How It Works
Capture face images of registered users.
Train the system using stored face encodings.
Start webcam attendance session.
Detect and recognize faces in real-time.
Match detected faces with trained dataset.
Automatically mark attendance.
Generate attendance report in Excel format.


How it Works ,

Start System
     ↓
Capture Face via Webcam
     ↓
Detect Face using OpenCV
     ↓
Recognize Face with Trained Model
     ↓
Compare Face Embeddings
     ↓
Match Found?
   ↙       ↘
 Yes        No
  ↓          ↓
Mark Attendance
  ↓
Generate Excel Report
  ↓
Continue Scanning / Stop System
