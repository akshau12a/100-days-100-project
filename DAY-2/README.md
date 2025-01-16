# Real-Time Face Detection Using OpenCV 🎥💻

A Python-based real-time face detection application leveraging OpenCV's Haar Cascade Classifier. The program captures video from the camera, detects faces in real-time, and overlays bounding boxes around detected faces.

---

## Features

- **Real-time face detection** using Haar Cascades.
- **Dynamic visualization** with bounding boxes for detected faces.
- User-friendly interface with the ability to quit using the `q` key.
- Lightweight and efficient for live video streams.

---

## Technologies Used

- **Python**
- **OpenCV**

---

## How It Works

1. Captures video from the default camera.
2. Converts video frames to grayscale for optimized detection.
3. Detects faces and draws green rectangles around them.
4. Displays the output in a real-time video window.

---

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.x
- OpenCV library

To install OpenCV, use the command:

```bash
pip install opencv-python
