# Pothole AI

Pothole AI is an iOS app that uses on-device machine learning to detect potholes in real time using a smartphone camera. The app runs a YOLOv11 computer vision model through Apple Core ML and logs detected potholes with GPS coordinates for road monitoring and infrastructure maintenance.

## Features
- Real-time pothole detection
- On-device YOLOv11 inference
- GPS-based pothole logging
- Interactive map visualization
- Privacy-focused edge AI
- No cloud processing required

## Tech Stack
- Swift
- Xcode
- Core ML
- Vision
- AVFoundation
- Core Location
- YOLOv11
- Google Colab
- Ultralytics
- PyTorch

## How It Works
1. The phone camera captures road video.
2. Frames are sampled and preprocessed.
3. A YOLOv11 model detects potholes on-device.
4. Detections are shown with bounding boxes.
5. GPS coordinates are logged and displayed on a map.

## Model Training
The YOLOv11 model was trained using a pothole detection dataset and exported to Core ML for iOS deployment.

## Demo Video
https://www.youtube.com/watch?v=bpN9TJ-kavI&t=1s

## Project Purpose
This project explores how edge machine learning can help detect hidden infrastructure problems early, supporting safer roads and more sustainable maintenance.

## Author
Ivan Turan
