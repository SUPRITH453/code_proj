# code_proj

Face Detection, Age, and Gender Estimation
This Python script utilizes OpenCV's deep neural networks for face detection and estimates the age and gender of detected faces in real-time through a webcam feed.

Dependencies

Ensure you have the following dependencies installed:
Python (3.x recommended)
OpenCV (cv2)
NumPy
IPython (for Jupyter Notebook integration)

Installation

Clone or download this repository to your local machine.

Install the required dependencies using pip:

pip install opencv-python numpy ipython

Usage

Run the script face_detection_age_gender.py.
Ensure your webcam is connected and functional.
The script will start capturing video from the webcam and display it in a window.
Detected faces will be outlined with bounding boxes, and their estimated gender and age will be displayed near each face.
Press 'q' to exit the program.

Files

face_detection_age_gender.py: The main Python script for real-time face detection, age, and gender estimation.
opencv_face_detector.pbtxt and opencv_face_detector_uint8.pb: Pre-trained models for face detection.
age_deploy.prototxt and age_net.caffemodel: Pre-trained models for age estimation.
gender_deploy.prototxt and gender_net.caffemodel: Pre-trained models for gender prediction.

Credits

This script is inspired by various tutorials and resources on computer vision and deep learning.
OpenCV for providing pre-trained models and a robust library for computer vision tasks.
