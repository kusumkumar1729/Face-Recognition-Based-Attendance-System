# 👤 Face Recognition-Based Attendance System

This is a Flask-based web application for a **Face Recognition-Based Attendance System**. The system uses the **Haar Cascade algorithm** for face detection, the **K-Nearest Neighbors (KNN) Classifier** for face recognition, and **OpenCV** for real-time face recognition. It automates student attendance by recognizing faces through a webcam, making the process faster and more efficient.

---

## 🚀 Features

- 🧠 **Face Detection & Recognition**
  - Haar Cascade algorithm for real-time face detection.
  - KNN Classifier for face recognition.
  
- 📝 **Automatic Attendance Tracking**
  - Matches detected faces with known students and logs attendance.

- 🌐 **Flask Web Application**
  - Flask backend handles logic, with a responsive HTML/CSS/JS frontend.

- 📷 **Webcam Integration**
  - Uses OpenCV to access the computer's webcam and capture live video.

- 🗃️ **Student Database**
  - Stores student information and attendance records using SQLite.

- ➕ **Add New Students**
  - Easily train the system to recognize new faces.

---

## 🛠️ Technologies Used

| Technology | Description |
|------------|-------------|
| 🐍 Python | Core programming language |
| 🔍 Haar Cascade | Face detection |
| 🤖 KNN Classifier | Machine learning algorithm for face recognition |
| 🎥 OpenCV | Real-time image/video processing |
| 🌐 Flask | Lightweight Python web framework |
| 🗂️ SQLite | Embedded database for student and attendance data |
| 💻 HTML/CSS/JS | Frontend interface |


## 🧪 Installation

### Prerequisites

Make sure Python 3.x is installed. Then, install the required libraries:

```bash
pip install flask opencv-python numpy scikit-learn
```
## 📁 Clone the Repository
```bash
git clone https://github.com/your-username/Face-Recognition-Based-Attendance-System.git
cd Face-Recognition-Based-Attendance-System
```
## ▶️ Run the Application
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
python app.py
```
## Then open your browser and go to:
```bash
http://127.0.0.1:5000
```



