# Facial Recognition Project

## Overview
This project implements a facial recognition system using **NumPy** and **OpenCV** for image processing, **Flask** for serving the application as an API, **Docker** for containerization, and **GitHub Actions** for CI/CD pipeline automation. The system is capable of detecting and recognizing faces in real-time video streams or uploaded images. The purpose of this project is to explore the facial recognition technology and demonstrate the power of modern computer vision libraries and frameworks.

## Features
- **Face Detection**: Uses OpenCV's pre-trained Haar Cascade classifiers to detect faces in images or video streams.
- **Face Recognition**: Utilizes OpenCV’s face recognition model to match detected faces against a pre-built dataset of known faces.
- **API Endpoints**: Provides a REST API with endpoints for image upload and recognition, allowing users to receive recognition results.
- **Real-Time Recognition**: Supports real-time facial recognition using a webcam or video input stream.

## Technologies Used
- **NumPy**: For efficient numerical computation and array manipulation.
- **OpenCV**: To perform image processing tasks, such as face detection and recognition.
- **Flask**: Provides a simple API server for handling image upload and recognition requests.
- **Docker**: Ensures consistency and ease of deployment by containerizing the application and its dependencies.
- **GitHub Actions**: Automates testing and deployment pipelines to improve code quality and speed up development.

## Setup 
- Docker
- Python 3.9 or above

## How It Works
- **Face Detection**: Upon receiving an image or video frame, the system detects all faces present using OpenCV's Haar Cascade or DNN-based face detectors.
- **Face Recognition**: The detected faces are then compared against a pre-trained dataset of faces using OpenCV’s face recognizer, which identifies known faces.
- **API Response**: If a face is recognized, the API returns the name of the recognized individual, along with the detection coordinates.