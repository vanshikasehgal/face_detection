**Real-Time Face Detection with OpenCV**

This project captures live video from your webcam and detects faces in real-time using OpenCV’s Haar Cascade Classifier. It provides a hands-on demonstration of computer vision techniques for detecting human faces in dynamic environments.

**Project Overview**

The program uses OpenCV’s pre-trained Haar Cascade model to:

Detect faces within each frame captured from a video stream
Draw bounding boxes around each detected face
Provide continuous, real-time feedback to the user


**Prerequisites**


Python 3.x: Ensure Python 3 is installed.
OpenCV: Install via pip install opencv-python.
Haar Cascade XML File: Download haarcascade_frontalface_default.xml and place it in the project directory.
Getting Started

Clone the Repository:

git clone  https://github.com/vanshikasehgal/face_detection.git

Navigate to the Directory:

cd Real-Time-Face-Detection

Install Dependencies:

pip install opencv-python


**Running the Project**


To start detecting faces:

python face_detection.py
Once the program starts:

A window will appear showing a live video feed from your webcam.
Faces detected in real-time are highlighted with green rectangles.
Press 'q' to exit the program and close the video window.


**Code Details**
face_detection.py: The main script that handles:
Video capture from the default webcam
Conversion of frames to grayscale for optimal performance
Face detection using detectMultiScale with tunable parameters
Real-time visualization with bounding boxes around detected faces


**Parameter Options:**

minNeighbors: Controls the threshold for face detection accuracy.
minSize: Specifies the minimum size for detected faces (default: (100, 100)).


**Example Output**


When you run the script, you’ll see a window similar to this:


      Real-Time Face Detection      
       (Press 'q' to exit)         

Detected faces will be outlined with green rectangles.


**Future Enhancements**


Consider adding features such as:

Eye and smile detection: Additional Haar cascades for eye and smile detection
Face recognition: Implement facial recognition using OpenCV’s face recognition libraries
Emotion detection: Detect emotions based on facial expressions (requires an additional model)


**License**


This project is licensed under the MIT License.

**Acknowledgments**


Special thanks to the OpenCV team for providing the Haar Cascade Classifiers.
