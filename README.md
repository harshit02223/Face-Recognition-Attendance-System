# Face Recognition Attendance System 🎓📸

An AI-powered, real-time facial recognition system for automated attendance tracking in classrooms or offices. This project uses Python, OpenCV, face_recognition, and machine learning models to streamline the attendance process.

---

## 🚀 Features

- 📷 Real-time face detection and recognition
- 🧠 Machine learning model training using LBPH / CNN
- 📊 Attendance records stored in Excel format
- 🔐 Secure login with password and username
- 🔁 Dynamic dataset creation and model updates
- 💾 Data encryption and log history for security

---

## 🛠️ Technologies Used

- Python 3.x
- OpenCV
- face_recognition
- pandas
- numpy
- tkinter (for GUI)
- os, shutil, time, datetime

---

## 📁 Folder Structure

```bash
FaceRecognitionAttendanceSystem/
│
├── data/
│   ├── datasets/              # Stored face images for each student
│   └── attendance_records/    # Excel files with attendance logs
│
├── models/
│   └── trained_model.pkl      # Saved model for recognition
│
├── src/
│   ├── dataset_creator.py     # For capturing images and saving datasets
│   ├── model_trainer.py       # Model training logic
│   ├── face_recognition.py    # Real-time recognition logic
│   ├── gui.py                 # UI logic
│   └── security.py            # Authentication & logging
│
├── assets/
│   ├── screenshots/           # UI and system screenshots
│   └── diagrams/              # Architecture/flowcharts
│
├── requirements.txt           # Required packages
├── README.md                  # Project description
├── LICENSE                    # Your preferred license (MIT recommended)
├── .gitignore                 # Files/folders to ignore in Git
└── main.py                    # App entry point
