# CNN_Projects
CNN-Based Vehicle Number Plate Recognition

This project uses Convolutional Neural Networks (CNN) combined with OpenCV and TensorFlow to detect, segment, and recognize vehicle license plates from images. The system first identifies the number plate region from the vehicle image and then segments each character for recognition using a CNN trained on labeled alphanumeric data.
🧠 Overview

Automatic Number Plate Recognition (ANPR) is a key component of intelligent transportation systems.
This project automates vehicle number plate detection and recognition using deep learning.

Core steps include:

Detecting the vehicle’s license plate using a trained Haar Cascade classifier.

Preprocessing and segmenting individual characters from the detected plate.

Recognizing each character using a trained CNN classifier.

✨ Features
Detects number plates from vehicle images using OpenCV’s Haar Cascade Classifier.

Segments individual characters from the plate region.

Recognizes characters (A–Z, 0–9) using a CNN trained on labeled data.

Computes model accuracy and F1-score for evaluation.

Visualization support for intermediate stages (plate detection, segmentation, and prediction).

🔄 Workflow

Input Image → Load vehicle image.

Plate Detection → Detect plate region using Haar Cascade.

Segmentation → Extract individual characters via contour detection.

Preprocessing → Normalize and resize character images (28×28).

CNN Classification → Predict each character label.

Result Generation → Combine predictions to form the full plate number.
