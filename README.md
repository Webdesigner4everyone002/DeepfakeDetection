# 🧠 Deepfake Detection using Deep Learning

> A deep learning-based system to detect AI-generated deepfake images and videos using CNNs and OpenCV.

## 🔍 Overview

Deepfakes are hyper-realistic manipulations of facial images or videos created using AI techniques. While they showcase technological advancements, they also pose serious risks in misinformation, identity fraud, and media manipulation.

This project aims to build an **end-to-end deepfake detection pipeline** that classifies input media as *real* or *fake* with high accuracy using deep learning.

## 📊 Dataset

- **Name:** Deepfake Dataset (3.7 GB)
- **Content:** Labeled real and fake videos/images
- **Processing:** Frame extraction using OpenCV, resized and normalized for CNN input.

## ⚙️ Tech Stack

- Python, OpenCV
- TensorFlow / Keras (CNN)
- NumPy, Matplotlib
- Scikit-learn (for evaluation metrics)

## 🛠️ Key Features

- ✅ Frame-level video analysis using OpenCV
- ✅ CNN model trained on 3.7 GB of deepfake dataset
- ✅ High-accuracy classification of real vs fake
- ✅ End-to-end pipeline: Data preprocessing → Training → Evaluation

## 🧪 What I Learned

- Building robust preprocessing pipelines for visual data
- Designing and training convolutional neural networks for classification
- Evaluating model performance using accuracy, precision, recall, and F1-score
- Real-time detection using OpenCV and video frame analysis

## 📷 Sample Output

| Input Frame | Prediction |
|-------------|------------|
| ![real](examples/real.png) | Real |
| ![fake](examples/fake.png) | Fake |

