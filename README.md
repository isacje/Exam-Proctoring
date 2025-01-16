# Automatic Detection of Students’ Engagement During Online Learning

## Project Overview
This project proposes a system to automatically detect student engagement in online learning environments using a bagging ensemble deep learning approach. The system analyzes real-time facial expressions and classifies engagement levels, enabling educators to adapt teaching strategies effectively.

## Features
- Utilizes **Convolutional Neural Networks (CNNs)** and **ResNet architectures**.
- Employs pre-trained models like **ResNet18** and **ResNet50** with transfer learning.
- Processes data from the **DAiSEE** dataset for comprehensive analysis.
- Real-time detection of engagement levels: **Very Low**, **Low**, **High**, and **Very High**.
- Supports multimodal data, including facial expressions, head movements, and eye tracking.

## System Architecture
The project consists of:
1. **Data Preprocessing**: Standardizing and preparing data.
2. **Feature Reduction**: Using techniques like SVD for dimensionality reduction.
3. **Model Training**: Bagging ensemble of ResNet models.
4. **Ensemble Prediction**: Aggregating predictions using a soft voting mechanism.
5. **Performance Evaluation**: Testing and analyzing model accuracy.

## Requirements

### Software
- **Operating System**: Windows 10 or later
- **Programming Language**: Python
- Libraries: OpenFace, TensorFlow, Keras

### Hardware
- **Processor**: Intel i3 or above
- **RAM**: 8 GB or more
- **Storage**: 500 GB or more
- **Webcam**: Internal/External for video capture

## Results
- Achieved **99.8% accuracy** using ResNet18 for engagement detection.
- Effectively identifies emotions like happiness, anger, and surprise.

## Future Work
- Explore additional modalities for enhanced accuracy.
- Expand to diverse educational settings and course structures.
