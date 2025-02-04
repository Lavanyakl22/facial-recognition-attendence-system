# Facial Recognition Attendance System

A Python-based attendance system using facial recognition with OpenCV, NumPy, and face_recognition libraries.

## Short Description

This project implements a facial recognition-based attendance system.  It captures images from a camera or webcam, detects faces, compares them against a database of known faces, and marks attendance accordingly.  It provides a simple and efficient way to automate attendance tracking, eliminating the need for manual roll calls or sign-in sheets.

## Features

* **Real-time Face Detection:** Utilizes OpenCV (cv2) to detect faces in real-time from a camera or video feed.
* **Face Recognition:** Employs the `face_recognition` library, built on dlib, for accurate and robust face recognition.  It generates face encodings for comparison.
* **Attendance Marking:**  Records attendance by comparing detected faces against a pre-existing database of known faces (encodings).
* **Data Storage:**  Stores attendance data (e.g., timestamps, names) in a structured format (e.g., CSV, text file - you can choose your preferred method).  The example code demonstrates basic CSV storage.
* **Customizable Threshold:** Allows adjustment of the face match tolerance/threshold for balancing accuracy and speed.
* **Image/Video Input:** Supports both image files and video streams (webcam or video files) as input sources.
* **Easy to Use:**  Designed for simplicity and ease of use, with clear instructions and a straightforward codebase.
* **Cross-Platform Compatibility:**  Should work across different operating systems (Windows, macOS, Linux) with Python and the required libraries installed.


## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/Lavanyakl22/facial-recognition-attendence-system
cd Facial-Recognition-Attendance
```
2. **Create a virtual environment**
   
```bash
python3 -m venv .venv  # Create the environment
source .venv/bin/activate  # Activate on Linux/macOS
.venv\Scripts\activate  # Activate on Windows
```

3. **Install the required packages:**
```bash
pip install -r requirements.txt
```

4. **Run the script**
```bash
python attendance.py
```
