# Rock-Paper-Scissors Object Detection

A Computer Vision project demonstrating how to train **YOLO26** on a custom **Rock-Paper-Scissors dataset** for multi-class object detection using the Ultralytics framework and Google Colab.

The model is trained to detect three classes:

- 🪨 Rock
- 📄 Paper
- ✂️ Scissors

The project covers dataset preparation, YOLO26 model training, validation, prediction, and model export.

---

## 📌 Project Overview

Object detection is a fundamental Computer Vision task that involves identifying objects in an image and locating them using bounding boxes.

In this project, a pretrained **YOLO26** model is fine-tuned on a custom Rock-Paper-Scissors dataset.

The complete workflow includes:

```text
Custom Dataset
      ↓
Dataset Preparation
      ↓
YOLO26 Pretrained Model
      ↓
Model Training
      ↓
Model Validation
      ↓
Object Detection
      ↓
Prediction Visualization
      ↓
Model Export
