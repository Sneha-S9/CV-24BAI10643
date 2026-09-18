Smart Helmet & Rider Safety Detection System
Overview
Smart Helmet & Rider Safety Detection System is a Computer Vision project that uses a YOLO-based object detection model to identify motorcycles, helmets, and riders without helmets.

The system helps determine the safety status of motorcycle riders from images and live webcam input.

Features
🖼️ Image-based helmet detection
🎥 Real-time webcam detection
🏍️ Motorcycle detection
🪖 Helmet detection
⚠️ Without-helmet detection
🚦 Automatic safety status
📊 Safety detection analytics
🧪 Automated testing using pytest
Technologies Used
Python
YOLO
Ultralytics
OpenCV
Streamlit
Streamlit-WebRTC
NumPy
Pandas
Pillow
Pytest
Project Structure
vityatri project/
│
├── dataset/
│   ├── images/
│   │   ├── train/
│   │   ├── val/
│   │   └── test/
│   └── labels/
│       ├── train/
│       ├── val/
│       └── test/
│
├── models/
│
├── src/
│   ├── image_detection.py
│   ├── webcam_detection.py
│   └── safety_analytics.py
│
├── tests/
│   └── test_safety_analytics.py
│
├── runs/
│
├── app.py
├── SmartHelmetDetection.py
├── data.yaml
├── requirements.txt
└── README.md
