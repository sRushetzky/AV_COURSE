# Traffic Sign Detection System

## Overview
This project implements a **Traffic Sign Detection and Classification system** designed for autonomous driving environments.

The system detects traffic signs and road objects from:

- Images
- Videos
- Live camera feed

It combines **YOLO object detection**, **traffic sign classification**, and **OCR** to recognize speed limit signs and other traffic signs.

The output includes:

- Bounding boxes around detected objects
- Classification labels
- Confidence scores
- Warning messages for important signs

Detected results are automatically saved to disk.

---

# Features

✔ Detect traffic signs in images  
✔ Detect traffic signs in videos  
✔ Real-time detection from camera  
✔ Speed limit recognition using OCR  
✔ Object detection (cars, pedestrians, bicycles, etc.)  
✔ Pause / Resume video processing  
✔ Automatic saving of detection results  

---

# Technologies Used

- Python
- OpenCV
- YOLOv8 (Ultralytics)
- PyTorch
- HuggingFace Transformers
- EasyOCR

---

# Installation

## 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/traffic-sign-detection.git
cd traffic-sign-detection
