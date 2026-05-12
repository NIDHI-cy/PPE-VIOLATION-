PPE-VIOLATION-DETECTION-ALERT-SYSTEM-USING-AI

An AI-powered real-time PPE (Personal Protective Equipment) Violation Detection and Alert System developed using YOLOv11, OpenCV, and Flask. The system detects whether workers are wearing required safety equipment such as helmets and safety vests from video streams or CCTV feeds and automatically generates alerts for violations.

Overview

This project focuses on improving workplace safety in industrial environments by automating PPE compliance monitoring using deep learning and computer vision techniques.

The system:

Detects persons, helmets, and safety vests in real time
Identifies PPE violations automatically
Supports both prerecorded videos and live RTSP camera streams
Sends automated email alerts with violation snapshots
Displays processed detection output through a web interface
Features
Real-time PPE violation detection
YOLOv11-based object detection
Live CCTV/RTSP stream support
Upload and analyze prerecorded videos
Automated email alert system
Downloadable violation reports
Dual display for raw and processed video
Flask-based backend integration
OpenCV frame extraction and processing
Technologies Used
Python
YOLOv11
OpenCV
Flask
HTML/CSS/JavaScript
SMTP (Email Alerts)
System Workflow
Video input is received from uploaded video or RTSP stream
OpenCV extracts frames from the video
Selected frames are passed to YOLOv11 for inference
Objects such as persons, helmets, and vests are detected
PPE compliance logic identifies violations
Bounding boxes and labels are generated
Automated alerts and reports are triggered
Processed output is streamed to the frontend
Dataset

The model was trained using an annotated PPE dataset containing approximately 20,000 images with classes such as:

Person
Helmet
Safety Vest

The dataset was divided into:

70% Training Data
30% Testing and Validation Data

Images were annotated using bounding boxes under varying workplace environments and lighting conditions.
