# YOLOv8 Object Detection System

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![Ultralytics](https://img.shields.io/badge/Ultralytics-YOLOv8-FFA500)](https://ultralytics.com)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.5%2B-green)](https://opencv.org)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)
## Author

Hafeez Ahmed
BS Artificial Intelligence Student
Pakistan

GitHub: https://github.com/hafeezgee
## 🧠 Project Overview
A complete, real-time object detection system built using **YOLOv8** (Ultralytics) that can detect and classify 80+ object types in images, videos, and webcam streams. This project demonstrates end-to-end deep learning application development — from model selection and inference to interactive UI design.

---

## 🎯 Problem Statement
Object detection is a fundamental computer vision task essential for autonomous vehicles, surveillance systems, medical imaging, and robotics. The goal of this project is to create an accurate, fast, and user-friendly detection system that can run in real-time on standard hardware, making cutting-edge AI accessible.

---

## 🧱 Architecture & Workflow

1. **Model**: YOLOv8 nano/small/medium (selectable) pre-trained on COCO dataset.
2. **Inference Pipeline**:
   - Input handling (image upload, video file, webcam capture)
   - Preprocessing & resizing to model input dimensions
   - Forward pass through YOLOv8 backbone, neck, and head
   - Non-max suppression to filter overlapping boxes
   - Postprocessing to plot bounding boxes & labels with confidence scores
3. **Interactive Interface**: Jupyter/Colab widgets for confidence threshold, model selection, real-time capture — now converted into clean reusable Python functions.

---

## ⚙️ Tech Stack

| Category          | Tools / Libraries                          |
|-------------------|--------------------------------------------|
| Language          | Python 3.8+                                |
| Deep Learning     | Ultralytics YOLOv8, PyTorch                |
| Computer Vision   | OpenCV, PIL                                |
| Visualization     | Matplotlib                                 |
| Interactive UI    | ipywidgets (Colab), OpenCV highgui (local) |
| Environment       | Google Colab (GPU), Local Python env       |

---

## 📊 Model & Dataset

- **Model**: YOLOv8n (Nano) / YOLOv8s (Small) / YOLOv8m (Medium)
- **Pre-trained weights**: `yolov8n.pt` (fastest), `yolov8s.pt` (balanced), `yolov8m.pt` (accurate)
- **Dataset**: [MS COCO](https://cocodataset.org/) — 80 object categories (person, car, bottle, cell phone, etc.)

---

## 🚀 Features

- ✅ Real-time detection on images
- ✅ Video file processing with annotated output
- ✅ Webcam live capture (photo snapshot mode in Colab)
- ✅ Interactive confidence threshold & model selection
- ✅ Batch processing of multiple images
- ✅ Performance benchmarking across models
- ✅ Modular code ready for deployment (Streamlit, Flask)

---
## 📸 Results

### Webcam Detection

![Webcam Detection](results/web_cam.jpg)

### Uploaded Image Detection

![Uploaded Image Detection](results/upload_pictures.jpg)

## ▶️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/hafeezgee/yolo-object-detection.git
cd yolo-object-detection
