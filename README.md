# Human Activity Recognition (HAR) Using Smartphone Sensors

## Overview
This project focuses on Human Activity Recognition (HAR) using smartphone inertial sensor data from the UCI-HAR dataset. Multiple machine learning and deep learning models were implemented and compared for recognizing human activities such as walking, sitting, standing, and lying.

## Features
- UCI-HAR Dataset
- SMOTE for class imbalance handling
- Classical ML models:
  - Support Vector Machine (SVM)
  - Random Forest
- Deep Learning models:
  - 1D CNN
  - LSTM
  - CNN-LSTM
  - CNN-BiLSTM
- TensorFlow Lite conversion
- Edge deployment optimization

## Technologies Used
- Python
- TensorFlow
- Scikit-learn
- NumPy
- Google Colab

## Dataset
UCI Human Activity Recognition Dataset:
https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones

## Best Result
CNN-BiLSTM achieved:
- Accuracy: 92.87%
- F1-score: 0.9293

## Edge Deployment
The trained 1D CNN model was converted into TensorFlow Lite format with quantization for lightweight edge deployment.

## Team Members
- Khushvir Singh Maan
- Krishna Saini
- Krishna Gupta
- Divyanshi Dhingra

## Project Type
B.Tech Final Year Project