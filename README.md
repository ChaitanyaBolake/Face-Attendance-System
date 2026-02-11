# Face-Attendance-System
This system is developed using Python, OpenCV, and the face_recognition library. It captures facial images, encodes them, and matches live webcam input with stored data to mark attendance automatically. The attendance data is saved in CSV format with date and time.

Face Recognition-Based Attendance Monitoring System 📸
A contactless, automated attendance system that uses facial recognition technology to track student or employee attendance in real-time. Built with Python, OpenCV, and Tkinter.
📝 Abstract
This project automates the traditional attendance process by capturing real-time images via a webcam, detecting faces, and comparing them with a pre-stored database. It eliminates manual errors and proxy attendance while providing a user-friendly GUI for management.
🚀 Features
•	Real-time Face Detection: Uses OpenCV and Haarcascade Classifiers.
•	High-Accuracy Recognition: Utilizes the face_recognition library (dlib-based) for precise matching.
•	Automated Logging: Saves attendance with exact timestamps to a CSV file.
•	GUI Dashboard: Tkinter-based interface to register new users and view records.
•	Data Management: Uses Pandas for efficient data handling and CSV for portable storage.
🛠️ Technologies Used
•	Python: Core programming language.
•	OpenCV (cv2): For video capture and image processing.
•	face_recognition: For generating face encodings and comparisons.
•	Haarcascade Classifier: For initial face detection within the frame.
•	NumPy: For handling image arrays and mathematical operations.
•	Pandas: For organizing and reading attendance logs.
•	CSV Module: For storing attendance records.
•	OS & Datetime: For file management and timestamping.
⚙️ Installation & Setup
Follow these steps to set up the project on your local machine.
1. System Prerequisites
•	Python: Ensure Python 3.8 or higher is installed.
•	C++ Build Tools (Windows Users): The dlib library requires C++ compilers. If you face errors installing dlib, download the Visual Studio Build Tools and select "Desktop development with C++" during installation.
2. Clone the Repository
Open your terminal or command prompt and run:
git clone [https://github.com/ChaitanyaBolake/face-attendance-system.git](https://github.com/ChaitanyaBolake/face-attendance-system.git)
cd face-attendance-system
3. Create a Virtual Environment (Recommended)
It is best practice to use a virtual environment to manage dependencies.
# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
4. Install Dependencies
Install the required libraries step-by-step to avoid compilation errors.
Step 1: Install dlib Note: This may take a few minutes to compile.
pip install dlib
Step 2: Install Project Requirements
pip install OpenCV-python 
pip install face_recognition
pip intall Numpy
pip install Pandas
pip install Datetime
5. Setup Project Files
Ensure you have the necessary Haarcascade file in your project directory.
Download haarcascade_frontalface_default.xml from the OpenCV GitHub and place it in the root folder.
Create a folder named Images (to save student photos) and Attendance (to save CSV logs) if they don't exist.
6. Run the Application
Start the system by running the main Python script:
python main.py
📖 How to Use
Register a New Student:
1.	Enter the ID and Name in the GUI.
2.	Click "Take Images" to capture the face samples.
3.	Click "Save Profile" to store the encoding.
Take Attendance:
1.	Click "Track Attendance".
2.	The webcam will open; simply look at the camera. 3)Attendance is marked instantly when a match is found.
View Records: Open the generated CSV file in the Attendance folder or view via the GUI table.
🔮 Future Scope
Integration with a cloud-based database (Firebase/SQL). Mobile application support using Flutter. Liveness detection to prevent spoofing with photos.
👥 Contributors
•	Chaitanya Bolake - Lead Developer
o	Designed system architecture and core logic.
o	Implemented face detection and recognition algorithms using OpenCV.
o	Optimized real-time video processing performance.
•	Rushikesh Gadade - Co-Developer
o	Developed the user interface (GUI) using Tkinter.
o	Managed CSV database integration for automated logging.
o	Handled system integration and project documentation.

