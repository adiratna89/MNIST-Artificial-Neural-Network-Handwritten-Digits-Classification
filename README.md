<h1 align="center">Handwritten Digit Classification on MNIST Using Artificial Neural Network (MLP)</h1>

<p align="center">
  <b>A deep learning mini project for classifying handwritten digits (0–9) using a Multi-Layer Perceptron (ANN) model built with TensorFlow/Keras.</b>
</p>

<p align="center">
  <a href="https://github.com/adiratna89/MNIST-Artificial-Neural-Network-Handwritten-Digits-Classification">
    <img src="https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github" />
  </a>
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?style=for-the-badge&logo=tensorflow" />
  <img src="https://img.shields.io/badge/Keras-Neural%20Network-red?style=for-the-badge&logo=keras" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Task-Multi--Class%20Classification-6f42c1?style=flat-square" />
  <img src="https://img.shields.io/badge/Dataset-MNIST-0a9396?style=flat-square" />
  <img src="https://img.shields.io/badge/Model-MLP%20%7C%20ANN-ff6b6b?style=flat-square" />
  <img src="https://img.shields.io/badge/Accuracy-~97--98%25-success?style=flat-square" />
</p>

---

## Table of Contents

- [Project Overview](#project-overview)
- [Why This Project Matters](#why-this-project-matters)
- [Dataset Information](#dataset-information)
- [Project Snapshot](#project-snapshot)
- [Workflow Pipeline](#workflow-pipeline)
- [Data Preprocessing](#data-preprocessing)
- [Model Architecture](#model-architecture)
- [Training Configuration](#training-configuration)
- [Results and Insights](#results-and-insights)
- [Project Visuals](#project-visuals)
- [Tech Stack](#tech-stack)
- [Repository Structure](#repository-structure)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## Project Overview

This project focuses on **handwritten digit classification** using the famous **MNIST dataset** and an **Artificial Neural Network (MLP)** model.

The main goal is to classify grayscale images of digits from **0 to 9** by building a deep learning pipeline that includes:
- data loading
- image visualization
- preprocessing
- ANN model building
- model training
- validation
- prediction
- performance evaluation

---

## Why This Project Matters

This project represents an important step forward from traditional machine learning mini projects into the domain of **deep learning and image classification**.

It demonstrates:
- understanding of neural network-based classification
- practical usage of TensorFlow and Keras
- conversion of image data into model-ready input features
- evaluation of model performance through confusion matrix and visual predictions

It also shows visible growth in project presentation and repository quality compared to earlier GitHub uploads.

---

## Dataset Information

- **Dataset Name:** MNIST Handwritten Digits
- **Source:** Keras built-in dataset
- **Total Samples:** 70,000 images
- **Training Samples:** 60,000
- **Testing Samples:** 10,000
- **Image Size:** 28 × 28 pixels
- **Classes:** 10 digits (0–9)

---

## Project Snapshot

| Feature | Details |
|---------|---------|
| Problem Type | Multi-class Classification |
| Domain | Computer Vision / Deep Learning |
| Dataset | MNIST |
| Model Used | Artificial Neural Network (MLP) |
| Framework | TensorFlow / Keras |
| Input Shape | 28 × 28 grayscale image |
| Processed Input | Flattened 784-dimensional vector |
| Output | Predicted digit class (0–9) |
| Performance | Around 97–98% test accuracy |

---

## Workflow Pipeline

```text
MNIST Dataset
     ↓
Image Visualization
     ↓
Normalization
     ↓
Flattening (28×28 → 784)
     ↓
One-Hot Encoding
     ↓
ANN / MLP Model Building
     ↓
Training & Validation
     ↓
Model Evaluation
     ↓
Prediction & Error Analysis
```

---

## Data Preprocessing

Before training the model, the following preprocessing steps were applied:

- Pixel values were normalized to the range **[0, 1]**
- Each 28 × 28 image was flattened into a **784-dimensional vector**
- Class labels were transformed using **one-hot encoding**
- Training and testing sets were kept separate for proper evaluation

These steps prepared the image data for efficient learning using a dense neural network.

---

## Model Architecture

The model used in this project is a **Multi-Layer Perceptron (MLP)** built using fully connected dense layers.

### Architecture Summary

- **Input Layer:** 784 neurons
- **Hidden Layer 1:** 128 neurons with ReLU activation
- **Hidden Layer 2:** 64 neurons with ReLU activation
- **Output Layer:** 10 neurons with Softmax activation

### Model Goal

The ANN learns hidden numerical patterns from pixel intensities and predicts the most probable handwritten digit class.

---

## Training Configuration

- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Evaluation Metric:** Accuracy
- **Epochs:** 10
- **Batch Size:** 128
- **Validation Split:** 0.1

---

## Results and Insights

- The model achieved around **97–98% test accuracy**
- Training and validation accuracy remained consistently strong
- Loss decreased steadily across epochs, indicating good learning behavior
- The confusion matrix showed strong class-wise prediction performance
- A few misclassifications occurred between visually similar handwritten digits

This project shows that even a basic ANN/MLP can perform extremely well on structured image-classification tasks like MNIST.

---

## Project Visuals

### Training vs Validation Accuracy

<p align="center">
  <img src="Output_images/Accuracy%20Plot.png" width="750" alt="Training vs Validation Accuracy Plot" />
</p>

### Training vs Validation Loss

<p align="center">
  <img src="Output_images/Loss%20Plot.png" width="750" alt="Training vs Validation Loss Plot" />
</p>

### Confusion Matrix

<p align="center">
  <img src="Output_images/Confusion%20Matrix%20MNIST%20ANN.png" width="750" alt="Confusion Matrix for MNIST ANN Model" />
</p>

### Visual Predictions

<p align="center">
  <img src="Output_images/Visual%20Predictions.png" width="900" alt="Visual Predictions of MNIST Handwritten Digits" />
</p>

---

## Tech Stack

- **Programming Language:** Python
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
- **Deep Learning Framework:** TensorFlow / Keras
- **Environment:** Jupyter Notebook

---

## Repository Structure

```bash
MNIST-Artificial-Neural-Network-Handwritten-Digits-Classification/
│
├── Notebook(Python File)/
│   └── MNIST_Artificial_Neural_Network_Handwritten_Digits_Classification.ipynb
│
├── Output_images/
│   ├── Accuracy Plot.png
│   ├── Confusion Matrix MNIST ANN.png
│   ├── Loss Plot.png
│   └── Visual Predictions.png
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## Future Improvements

This project can be improved further by:

- implementing a **Convolutional Neural Network (CNN)** for stronger image feature extraction
- adding dropout for better regularization
- tuning hidden layers and neuron counts
- comparing ANN vs CNN performance
- deploying the trained model as a simple web-based digit recognizer

---

## Author

**Adiratna Kamble**  
Aspiring Data Scientist | Machine Learning & Deep Learning Enthusiast

<p align="left">
  <a href="https://www.linkedin.com/in/adiratna-kamble">
    <img src="https://img.shields.io/badge/LinkedIn-Adiratna%20Kamble-blue?style=for-the-badge&logo=linkedin" />
  </a>
</p>
