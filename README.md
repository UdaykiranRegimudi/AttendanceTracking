# Attendance Tracking System

The Attendance Tracking System is a face recognition-based attendance management application developed using Python. The system captures images of students, trains a facial recognition model, and tracks attendance by recognizing faces from a live camera feed.

##Screens


<img src="screens\GUI.jpg" alt="Home GUI"></img>
<img src="screens\GUI2.jpg" alt=" GUI"></img>
<img src="screens\GUI3.jpg" alt=" GUI"></img>
<img src="screens\GUI4.jpg" alt=" GUI"></img>
<img src="screens\GUI5.jpg" alt=" GUI"></img>

## Features

- *New Student Registration:* Capture images of new students and save their profiles.
- *Face Recognition:* Recognize registered students and mark their attendance.
- *Password Protection:* Secure certain actions with password verification.
- *CSV Storage:* Store student details and attendance records in CSV files.
- *GUI Interface:* User-friendly interface using Tkinter.

## Requirements

- Python 3.x
- OpenCV
- Numpy
- Pandas
- Pillow (PIL)
- Tkinter

## Installation

1. Clone the repository:
    bash
    git clone https://github.com/UdaykiranRegimudi/AttendanceTracking.git
    
    cd AttendanceTracking
    

2. Install the required packages:
    bash
    pip install opencv-python numpy pandas pillow
    

## Usage

1. *Run the application:*
    bash
    python main.py
    

2. *New Student Registration:*
    - Enter the student ID and name.
    - Click on "Take Images" to capture the student's images.
    - Click on "Save Profile" to save the student's profile (requires password).

3. *Take Attendance:*
    - Click on "Take Attendance" to start the face recognition process.
    - The system will recognize registered students and mark their attendance.

## File Structure

- main.py: Main application file.
- haarcascade_frontalface_default.xml: Haar cascade file for face detection.
- TrainingImage: Directory to store captured images.
- TrainingImageLabel: Directory to store the trained model.
- StudentDetails: Directory to store student details CSV file.
- Attendance: Directory to store attendance records.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

