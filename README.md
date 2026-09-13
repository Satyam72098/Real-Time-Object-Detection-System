# Real-Time-Object-Detection-System
Real-time object detection system using OpenCV DNN and SSD MobileNet V3 trained on the COCO dataset
# Real-Time Object Detection System

A real-time object detection system built with OpenCV's DNN module and the 
SSD MobileNet V3 model, capable of detecting and labeling 80 different object 
classes from a live webcam feed.

## Features
- Real-time detection via webcam using OpenCV VideoCapture
- Pre-trained SSD MobileNet V3 model (trained on COCO dataset)
- Bounding boxes with class labels and confidence scores
- Configurable detection threshold, frame size, and brightness

## Tech Stack
- Python
- OpenCV (cv2.dnn_DetectionModel)
- SSD MobileNet V3 (frozen_inference_graph.pb + config)
- COCO dataset (coco.names — 80 classes)

## Files
- `main.py` — main detection script
- `coco.names` — list of object class names
- `frozen_inference_graph.pb` — pre-trained model weights
- `ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt` — model config

## Requirements
```bash
pip install opencv-python
