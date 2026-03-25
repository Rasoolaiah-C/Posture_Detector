# 🧘‍♂️ Yoga Posture Detection System

## Overview
The Yoga Posture Detection System is a real-time web application that analyzes human body poses and provides feedback on yoga posture accuracy. It uses computer vision and deep learning to detect key body landmarks and compare them with predefined correct poses.

This system helps users perform yoga correctly, reducing the risk of injury and improving posture alignment.

---

## Features
- Real-time posture detection using webcam
- Pose estimation using MoveNet (TensorFlow.js)
- Visual feedback with skeletal keypoints
- Posture accuracy evaluation
- User-friendly UI built with React
- Runs directly in the browser (no backend required)

---

## Tech Stack

### Frontend
- React.js  
- JavaScript  
- Tailwind CSS  

### AI / ML
- TensorFlow.js  
- MoveNet (Pose Detection Model)

### Tools
- VS Code  
- Git & GitHub  

---

## How It Works
1. The application accesses the user's webcam.
2. The MoveNet model detects body keypoints (joints like shoulders, elbows, knees, etc.).
3. Keypoints are processed to calculate joint angles.
4. These angles are compared with predefined yoga posture standards.
5. The system provides real-time feedback on posture correctness.

---
