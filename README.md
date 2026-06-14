# Handwritten Character Recognition using CNN

## Overview

This project is a Handwritten Character Recognition system developed as part of the CodeAlpha Machine Learning Internship. The model uses a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset.

The objective is to classify handwritten digits (0–9) with high accuracy using deep learning and computer vision techniques.

---

## Dataset

**MNIST Handwritten Digits Dataset**

- Total Images: 70,000
- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels
- Classes: 10 (Digits 0–9)

The dataset is automatically loaded using TensorFlow/Keras.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Deep Learning Architecture

The model consists of:

1. Convolutional Layer (32 filters)
2. Max Pooling Layer
3. Convolutional Layer (64 filters)
4. Max Pooling Layer
5. Flatten Layer
6. Dense Layer (128 neurons)
7. Output Layer (10 neurons with Softmax activation)

---

## Project Workflow

1. Load MNIST Dataset
2. Data Preprocessing and Normalization
3. Build CNN Architecture
4. Train the Model
5. Evaluate Model Performance
6. Generate Predictions
7. Visualize Results
8. Save Trained Model

---

## Visualizations Included

- Sample Handwritten Digits
- Training vs Validation Accuracy Graph
- Training vs Validation Loss Graph
- Confusion Matrix
- Actual vs Predicted Digits
- Classification Report

---

## Model Performance

- Deep Learning Model: Convolutional Neural Network (CNN)
- Dataset: MNIST
- Classes: 10 Digits (0–9)
- Test Accuracy: Approximately 98%–99%

---

## How to Run

### 1. Install Dependencies

pip install -r requirements.txt

### 2. Open Jupyter Notebook

jupyter notebook

### 3. Run

Open:

handwritten_character_recognition.ipynb

and run all cells.

---

## Files Included

```text
CodeAlpha_HandwrittenCharacterRecognition
│
├── handwritten_character_recognition.ipynb
├── mnist_cnn_model.h5
├── README.md
└── screenshots
```

---

## Applications

- Digit Recognition Systems
- Optical Character Recognition (OCR)
- Automated Form Processing
- Bank Check Processing
- Postal Code Recognition
- Educational AI Applications

---

## Future Improvements

- Recognition of handwritten alphabets using EMNIST
- Recognition of full words and sentences
- Real-time digit recognition using webcam input
- Deployment as a web application

---

## Author

Ashutosh Agrawal

B.Tech CSE
Government College of Engineering, Kalahandi

CodeAlpha Machine Learning Internship
