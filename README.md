# Face-Detection
Face Detection using OpenCV
This project implements real-time face detection using OpenCV, a popular open-source computer vision library. The system uses a pre-trained Haar Cascade classifier to detect faces in both images and video streams.

Features
Real-time face detection from a webcam feed
Face detection in static images
Option to draw bounding boxes around detected faces
Easy to use and integrate with other applications
Technologies Used
Python
OpenCV
How it Works
Load the Haar Cascade classifier pre-trained model for face detection.
Capture frames from the webcam or load an image.
Detect faces in each frame and mark them with a bounding box.
Display the output with the detected faces in real time.
Installation
Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/face-detection-opencv.git
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the face detection script:
bash
Copy code
python face_detection.py
Demo
You can test the project by running the script, which will open a window displaying the live video feed with detected faces marked by rectangles.
