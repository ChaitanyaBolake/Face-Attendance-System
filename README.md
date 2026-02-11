# 🎯 Face Recognition Based Attendance System

An automated attendance management system built using **Python** and **Computer Vision**.  
The system detects and recognizes faces in real time through a webcam and automatically marks attendance with date and time.


## 📌 Project Objective

The main objective of this project is to eliminate manual attendance systems and prevent proxy attendance by using facial recognition technology. The system ensures accuracy, efficiency, and security in attendance tracking.



## 🚀 Features

- Face image capture and dataset creation
- Face training and encoding
- Real-time face recognition using webcam
- Automatic attendance marking
- Date and time recording
- CSV-based attendance storage
- Admin password protection
- User-friendly GUI (Tkinter)

---

## 🛠️ Technologies Used

- **Python**
- **OpenCV**
- **face_recognition**
- **NumPy**
- **Pandas**
- **Tkinter**
- **CSV Module**
- **OS Module**
- **Datetime Module**
- **Haarcascade Classifier**


## ⚙️ System Workflow

1. Register a new user by capturing face images.
2. Train the system to encode facial features.
3. Start real-time face recognition using webcam.
4. Match detected faces with stored encodings.
5. Mark attendance automatically in a CSV file.
6. Save attendance with Name, Date, and Time.


## 💻 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Face_Attendance_System.git
cd Face_Attendance_System

## Install Required library 
pip install opencv-python
pip install face-recognition
pip install numpy
pip install pandas



