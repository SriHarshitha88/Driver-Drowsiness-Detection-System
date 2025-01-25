# Driver Drowsiness Detection Alert System with OpenCV & Keras Using IP-webCam For Camera Connection

## Project Overview

This project aims to build a **Driver Drowsiness Detection System** using Python, OpenCV, and Keras. The system detects when a driver is feeling drowsy and alerts them by monitoring their eye movements in real-time using a webcam. The system is designed to prevent accidents caused by drivers falling asleep at the wheel.

## Technologies Used
- **Python** (3.7 recommended)
- **OpenCV** for image processing and webcam access
- **Keras** (with TensorFlow backend) for the deep learning model
- **Pygame** to play an alarm sound
- **IP-webcam** for mobile camera connection

## Dataset
- The dataset for this project was created manually by capturing eye images using a camera (IP-webcam).
- The dataset comprises around 7000 images of people's eyes under various lighting conditions.
- The images are labeled as **"Open"** or **"Closed"**.

## Model Architecture
The model is built using Convolutional Neural Networks (CNNs) in Keras. The architecture consists of the following layers:
- Convolutional layer: 32 nodes, kernel size 3
- Convolutional layer: 32 nodes, kernel size 3
- Convolutional layer: 64 nodes, kernel size 3
- Fully connected layer: 128 nodes
- Final fully connected layer: 2 nodes (for open or closed eyes)

## Prerequisites
- **OpenCV**: `pip install opencv-python`
- **TensorFlow**: `pip install tensorflow`
- **Keras**: `pip install keras`
- **Pygame**: `pip install pygame`

# Installation Instructions

# Guide on how to set up the project in a local environment.

# Clone the repository:
git clone <repository-url>

# Install dependencies:
pip install -r requirements.txt

# Usage

# A simple example on how to use the application.

# To start the drowsiness detection system:
python drowsiness_detection.py

# How It Works

# The system captures the driver’s face through the webcam.
# It detects facial features (like eyes) using pre-trained Haar cascade classifiers.
# If the eyes are detected as closed for too long, it triggers an alarm sound.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details


