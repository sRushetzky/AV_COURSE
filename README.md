# Traffic Sign Detection System

## Overview
This project implements a **Traffic Sign Detection and Classification system** for autonomous driving environments.

The system can detect traffic signs and road objects from:

- Images
- Videos
- Live camera

It combines **YOLOv8 object detection**, **traffic sign classification**, and **OCR** to identify speed limit signs and other road signs.

Detected objects are displayed with:

- Bounding boxes
- Labels
- Confidence scores
- Warning messages

All results are automatically saved.

---

# Technologies

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
```

## 2. Install dependencies

Make sure Python **3.9+** is installed.

```bash
pip install ultralytics opencv-python torch torchvision easyocr transformers pillow
```
pip uninstall opencv-python-headless
pip uninstall opencv-python
pip install opencv-python
---

# Required Model

Place the traffic sign detection model in:

```
models/traffic_signs.pt
```

The YOLO model (`yolov8n.pt`) will download automatically on first run.

---

# Project Structure

```
traffic-sign-detection
│
├── main.py
├── models
│   └── traffic_signs.pt
│
├── inputs
│   ├── images
│   └── videos
│
├── outputs
│   ├── images
│   └── videos
│
└── README.md
```

---

# Running the Project

Run the program:

```bash
python main.py
```

Menu:

```
1 - Image detection
2 - Video detection
3 - Camera detection
0 - Exit
```

---

# Controls (Video Mode)

| Key | Action |
|-----|------|
| P | Pause / Resume |
| Q | Exit |
| ESC | Exit |

---

# Output

Detection results are automatically saved to:

```
outputs/images
outputs/videos
```

Each detection includes a bounding box, label, and confidence score.

---

# Author

Developed as part of a **Software Development for Autonomous Vehicles course project**.
