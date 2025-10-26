# Pneumonia-Detection
# Chest X-ray Pneumonia Detection and Deployment

## Overview
Deep learning project for classifying chest X-ray images as Pneumonia or Normal using a custom CNN model.

## Model
- CNN with multiple Conv2D, MaxPooling, BatchNorm, and Dropout layers.
- Optimized using Adam optimizer and ReduceLROnPlateau scheduler.

## Data Processing
- Image resizing, normalization, augmentation (rotation, zoom, flip).
- Dataset: Chest X-ray Dataset (Pneumonia vs Normal).

## Deployment
Streamlit web app for real-time X-ray image upload and pneumonia prediction.

## Results
- Test accuracy: **92%**
- Evaluation: Confusion Matrix, Classification Report, Accuracy Curves.

## Tech Stack
Python | TensorFlow | Keras | OpenCV | Matplotlib | Seaborn | Streamlit

