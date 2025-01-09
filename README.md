# 🥔 Potato Leaf Disease Classification

## Overview
A deep learning model that classifies potato plant leaves into three categories: Early Blight, Late Blight, and Healthy. This tool helps farmers identify plant diseases early through image classification.

## 🛠️ Technologies Used
- Python 3.x
- TensorFlow 2.x
- Keras
- Matplotlib
- NumPy

## 🤖 Model Details
- Input: 256x256 RGB images
- Architecture: CNN with 6 convolutional layers
- Output: 3 classes (Early Blight, Late Blight, Healthy)
- Training Split: 80% training, 10% validation, 10% testing
- Accuracy metrics and visualization included

## Quick Start
```python
# Train model
python train.py

# Make prediction
python predict.py --image_path "path/to/image.jpg"
```

## ✨ Features
- Real-time disease classification
- Training visualization
- Prediction confidence scoring
- Model version control
- Saved model support
