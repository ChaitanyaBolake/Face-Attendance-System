# Face Recognition-Based Attendance Monitoring System 📸

A contactless, automated attendance system that uses facial recognition technology to track student or employee attendance in real-time. Built with Python, OpenCV, and Tkinter.

## 📝 Abstract
This project automates the traditional attendance process by capturing real-time images via a webcam, detecting faces, and comparing them with a pre-stored database. It eliminates manual errors and proxy attendance while providing a user-friendly GUI for management.

## 🚀 Features
- **Real-time Face Detection:** Uses OpenCV and Haarcascade Classifiers.
- **High-Accuracy Recognition:** Utilizes the `face_recognition` library (dlib-based) for precise matching.
- **Automated Logging:** Saves attendance with exact timestamps to a CSV file.
- **GUI Dashboard:** Tkinter-based interface to register new users and view records.
- **Data Management:** Uses Pandas for efficient data handling and CSV for portable storage.

## 🛠️ Technologies Used
- **Python:** Core programming language.
- **OpenCV (`cv2`):** For video capture and image processing.
- **face_recognition:** For generating face encodings and comparisons.
- **Haarcascade Classifier:** For initial face detection within the frame.
- **NumPy:** For handling image arrays and mathematical operations.
- **Pandas:** For organizing and reading attendance logs.
- **CSV Module:** For storing attendance records.
- **OS & Datetime:** For file management and timestamping.

📖 How to Use
Register a New Student:

Enter the ID and Name in the GUI.

Click "Take Images" to capture the face samples.

Click "Save Profile" to store the encoding.

Take Attendance:

Click "Track Attendance".

The webcam will open; simply look at the camera.

Attendance is marked instantly when a match is found.

View Records:

Open the generated CSV file in the Attendance folder or view via the GUI table.

🔮 Future Scope
Integration with a cloud-based database (Firebase/SQL).

Mobile application support using Flutter.

Liveness detection to prevent spoofing with photos.

🤝 Contributing

cmake
dlib
Would you like help
