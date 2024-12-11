# CapuEcho - Capuchin Bird Call Classifier 🦜

![Project Banner](#) <!-- Add your image link here -->

## Overview
**CapuEcho** is a deep learning project designed to classify Capuchin bird calls with high accuracy. Built using **TensorFlow** and **TensorFlow IO**, this tool is intended to assist researchers, conservationists, and bird enthusiasts in identifying Capuchin bird calls from audio recordings.

## Key Features
- **High Accuracy:** Achieved **94% accuracy** on a dataset of 810 audio samples.
- **Audio Preprocessing:** Leveraged **Short-Time Fourier Transform (STFT)** and spectrogram transformations for robust feature extraction.
- **Efficient Model Design:** Developed a lightweight **Convolutional Neural Network (CNN)** architecture with Conv2D and MaxPooling layers for binary classification.
- **Real-Time Classification:** Designed to handle real-time bird call detection tasks effectively.

## How It Works
1. **Data Preprocessing:**
   - Audio data is preprocessed using STFT to generate spectrograms.
   - Spectrograms are normalized and padded to ensure uniform input size.

2. **Model Architecture:**
   - Convolutional layers extract key features from the spectrograms.
   - MaxPooling layers reduce dimensionality, preventing overfitting.
   - Dense layers perform binary classification to detect Capuchin bird calls.

3. **Evaluation:**
   - The model is evaluated using metrics such as **accuracy**, **precision**, and **recall**.

## Prerequisites
- Python 3.8+
- TensorFlow 2.0+
- TensorFlow IO

## Results
- **Accuracy:** 94%
- **Dataset:** 810 audio samples
- **Key Metrics:**
  - Precision: High
  - Recall: High

