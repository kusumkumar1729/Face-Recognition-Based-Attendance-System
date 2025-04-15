# Face Recognition-Based Attendance System

This is a Flask-based web application for a Face Recognition-Based Attendance System. The system uses the **Haar Cascade algorithm** for face detection, the **K-Nearest Neighbors (KNN) Classifier** for face recognition, and **OpenCV** for real-time face recognition. It aims to automate the process of tracking student attendance by recognizing faces through a webcam, making the process faster and more efficient.

## Features

- **Face Detection & Recognition**: 
  - Uses the **Haar Cascade algorithm** to detect faces in real-time.
  - **KNN Classifier** is used for recognizing faces by comparing the captured face to a set of stored face data.
- **Attendance Tracking**: Automatically records attendance by matching faces to a database of known students.
- **Flask Backend**: Flask is used to handle the application logic, and the frontend is built using HTML, CSS, and JavaScript.
- **Real-Time Webcam Integration**: Uses the computer's webcam to capture and process live video for attendance marking.
- **Database**: Student information, including attendance records, are stored in a SQLite database.
- **Face Data Management**: New students can be added to the system by training the model on their images using KNN.
  
## Technologies Used

- **Flask**: A lightweight web framework for Python used to handle backend routes and logic.
- **Haar Cascade Algorithm**: A machine learning-based approach for object detection, used for face detection in this project.
- **K-Nearest Neighbors (KNN) Classifier**: A simple machine learning algorithm used for classifying faces based on the distance between feature vectors.
- **OpenCV**: An open-source computer vision library used to process real-time images and videos for face recognition.
- **SQLite**: A lightweight, serverless SQL database used to store student information and attendance records.
- **HTML/CSS/JavaScript**: For the frontend user interface and interaction.

## Installation

### Prerequisites

Ensure that Python 3.x is installed on your system. You will also need to install the following libraries:

- Flask
- OpenCV
- NumPy
- SQLite3
- scikit-learn (for KNN)

To install the required libraries, you can use the following `pip` commands:

```bash
pip install flask opencv-python numpy sqlite3 scikit-learn
```

## Clone the repository
```bash
git clone https://github.com/your-username/Face-Recognition-Based-Attendance-System.git
cd Face-Recognition-Based-Attendance-System
```
## Running the Application
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
python app.py

```

## Access the application at 
```bash
http://127.0.0.1:5000
```
