# Parkinson's Disease Prediction using Machine Learning

## Overview
The **Parkinson's Disease Prediction** project utilizes machine learning techniques to detect Parkinson's disease from voice recordings. By analyzing vocal features, the model aims to distinguish between healthy individuals and those with Parkinson's.

## Features
- Extracts relevant vocal biomarkers from audio recordings
- Implements multiple machine learning models for classification
- Provides performance evaluation metrics
- Enables early detection for improved diagnosis

## Installation
Clone the repository using:
```bash
git clone https://github.com/omar0930/Parkinson-s-Disease-Prediction-using-Machine-Learning.git
cd Parkinson-s-Disease-Prediction-using-Machine-Learning
```

## Dataset
The dataset consists of voice recordings from individuals diagnosed with Parkinson's and healthy controls. It includes extracted features such as jitter, shimmer, fundamental frequency, and harmonic-to-noise ratio.

## Workflow
1. Load and preprocess the dataset.
2. Extract relevant vocal features.
3. Split the dataset into training and testing sets.
4. Train machine learning models (e.g., SVM, Random Forest, Neural Networks).
5. Evaluate model performance using accuracy, precision, recall, and F1-score.
6. Deploy the trained model for real-time predictions.

## Results
The models achieved the following classification performance:
- **Support Vector Machine (SVM):** 87.4% accuracy
- **Random Forest Classifier:** 90.1% accuracy
- **Neural Network:** 92.7% accuracy

These results indicate that the neural network model provided the best classification performance. Further improvements can be achieved by using larger datasets and feature engineering.

## Technologies Used
- Python
- NumPy & Pandas
- Librosa (for audio processing)
- Scikit-learn
- TensorFlow/Keras (for deep learning models)
