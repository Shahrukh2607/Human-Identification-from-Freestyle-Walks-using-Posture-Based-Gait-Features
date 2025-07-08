# Human-Identification-from-Freestyle-Walks-using-Posture-Based-Gait-Features
This project is a real-time human identification system using posture-based gait features from freestyle walking. Combines computer vision and machine learning (Extra Trees, KNN, MLP) for accurate recognition in uncontrolled environments. Built with Python and OpenCV.
# 🧠 Human Identification from Freestyle Walks using Posture-Based Gait Features

This project implements a posture-based gait recognition system that identifies individuals from freestyle walking videos using machine learning and computer vision. Unlike conventional systems that rely mainly on step dynamics, our system focuses on posture variations such as joint angles and limb orientation to improve accuracy, even in uncontrolled environments.

---

## 🔍 Project Highlights

- **Posture Feature Extraction** using Kinect gait data
- **Machine Learning Models**:
  - Extra Trees Classifier
  - K-Nearest Neighbors (KNN)
  - Multi-Layer Perceptron (MLP)
- **Real-Time Recognition** from uploaded walking videos
- **Comparison Graphs** for performance metrics (Accuracy, Precision, Recall, F1-score)
- Built with **Python**, using **OpenCV**, **Matplotlib**, and **scikit-learn**

---

## 🚀 Modules Overview

- **Upload Kinect Gait Dataset**: Load raw gait sequences securely
- **Dataset Preprocessing**: Normalize, clean, and extract joint positions
- **Train/Test Split**: Stratified 80/20 data separation
- **Model Training**:
  - Extra Trees (88% accuracy)
  - KNN (83% accuracy)
  - MLP (75% accuracy)
- **Visualization**: Bar charts comparing all models
- **Live Gait Recognition**: Upload test videos to detect individuals in real time

---

## 💡 Use Cases

- Surveillance & Public Safety
- Smart Access Control Systems
- Healthcare Monitoring & Rehabilitation

---

## 🛠️ Technologies Used

- **Programming Language**: Python
- **Libraries**: OpenCV, scikit-learn, NumPy, Matplotlib
- **Approach**: Posture analysis via motion capture + deep learning
- **Supported OS**: Windows

---

## 📊 Accuracy Summary

| Model        | Accuracy | F1-Score |
|--------------|----------|----------|
| Extra Trees  | 88%      | High     |
| KNN          | 83%      | Good     |
| MLP          | 75%      | Moderate |

---

## 📽️ Demo Screens

- Upload gait video → System detects posture → Classifies person by ID in real time  
- Recognized individuals are labeled clearly on the screen as they walk  
- Performance is visualized through confusion matrices and bar charts
## 📌 How to Run the Project

1. Clone this repo
2. Double-click `run.bat` or run the main Python file
3. Upload the Kinect dataset
4. Preprocess → Train models → Compare → Test with live video

---
