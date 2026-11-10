# 🎯 Object Detection with TensorFlow 2.0

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Framework: TensorFlow 2.0](https://img.shields.io/badge/Framework-TensorFlow%202.0-FF6F00.svg?logo=tensorflow&logoColor=white)](#)

End-to-end real-time object detection and bounding box regression pipeline in TensorFlow 2.0.

## 📌 Overview
A modular computer vision implementation of modern object detection architectures in TensorFlow 2.0. Demonstrates anchor box generation, intersection-over-union (IoU) matching, bounding box coordinate regression, and non-maximum suppression (NMS) for multi-class detection.

## 🛠️ Key Capabilities
- **Feature Extraction:** Pre-trained convolutional backbones (ResNet / MobileNet) for spatial feature extraction.
- **Bounding Box Heads:** Multi-task loss combining classification cross-entropy and Smooth L1 regression.
- **Post-Processing:** Fast Non-Maximum Suppression (NMS) and confidence threshold filtering.

## 📂 Repository Contents
- `Object Detection using TF2.0.ipynb`: Full training, validation, and inference notebook with visual bounding box rendering.

## 🚀 Quickstart
```bash
git clone https://github.com/FirdowsRahaman/Object-Detection.git
cd Object-Detection
pip install tensorflow opencv-python matplotlib numpy
jupyter notebook "Object Detection using TF2.0.ipynb"
```

## 📄 License
This project is licensed under the MIT License.
