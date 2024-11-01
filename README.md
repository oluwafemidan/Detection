# Computer Vision Project: Pose, Face, Smile, and Hand Detection
## Overview
This project utilizes OpenCV, Mediapipe, and Haar Cascades to implement a comprehensive computer vision application capable of detecting human poses, faces, smiles, and hands in real-time. The goal is to create an interactive system that can recognize and respond to various human gestures and expressions.
## Technologies Used
- **OpenCV:** A powerful library for image processing and computer vision tasks.
- **Mediapipe:** A framework developed by Google for building multimodal applied machine learning pipelines, particularly useful for real-time facial and hand landmark detection.
- **Haar Cascades:** A machine learning object detection method used to identify objects in images or video streams.
## Installation
To set up the environment for this project, you need to install the required libraries. 
You can do this using pip:
bash
`pip install opencv-python mediapipe`

## Project Structure
The project is organized into several modules:
- pose_detection: Contains code for detecting human poses using Mediapipe.
- face_detection: Implements face detection using Haar Cascades.
- smile_detection: Uses facial landmarks to detect smiles.
- hand_detection: Detects hand landmarks and gestures.
