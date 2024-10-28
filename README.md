# face_detection
Real-Time Face Detection using OpenCV
This project implements real-time face detection using OpenCV’s Haar Cascade Classifier. It captures video from a webcam, detects faces within the frames, and draws rectangles around detected faces.

**Features**
Real-time video capture: Continuously captures frames from the webcam.
Face detection: Detects and highlights faces using a pre-trained Haar Cascade model.
Live visual feedback: Displays a real-time video feed with detected faces outlined.
**Requirements**
Python 3.x
OpenCV library
Haar Cascade XML file for frontal face detection
**Installation**
Clone the repository:
git clone https://github.com/vanshikasehgal/face_detection.git
**Navigate to the project directory:**
  cd Real-Time-Face-Detection
**Install the required packages:**
  pip install opencv-python
**Usage**
Ensure that the haarcascade_frontalface_default.xml file is in the same directory as face_detection.py.
Run the face_detection.py file:
  python face_detection.py
A new window should open displaying the live webcam feed with rectangles drawn around detected faces.
Code Explanation
**Loading the Classifier:** **The Haar Cascade XML file is loaded to detect faces.
**Capturing Video: ** Frames are captured continuously from the webcam.
**Face Detection:** The frames are converted to grayscale and passed to the classifier for face detection.
**Drawing Bounding Boxes:** For each detected face, a rectangle is drawn on the frame.
**Displaying Output:** The video feed with highlighted faces is displayed in a window.
**Example**
When you run the script, it will display a window like this:

-------------------------------
| Face Detection (Live Video) |
| Press 'q' to exit           |
-------------------------------
**Additional Notes**
You can adjust parameters such as minNeighbors and minSize in detectMultiScale for better detection results.
Press 'q' to exit the video feed.
