<h1 align="center">Handwritten Digit Classification on MNIST using Artificial Neural Network (MLP)</h1>

<p align="center">
  <b>A recruiter-friendly deep learning mini project that classifies handwritten digits (0–9) using a Multi-Layer Perceptron (ANN) model built with TensorFlow/Keras.</b>
</p>

<p align="center">
  <a href="https://github.com/adiratna89/MNIST-Artificial-Neural-Network-Handwritten-Digits-Classification">
    <img src="https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github" />
  </a>
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?style=for-the-badge&logo=tensorflow" />
  <img src="https://img.shields.io/badge/Keras-ANN-red?style=for-the-badge&logo=keras" />
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

## Overview

This project builds a handwritten digit recognition system using the **MNIST dataset** and an **Artificial Neural Network (MLP)** model.  
The task is to predict the correct digit class from grayscale handwritten image data.

It covers the complete workflow:

- data loading
- image visualization
- preprocessing
- neural network design
- training and validation
- evaluation
- prediction analysis

> This project reflects a clear progression from classical machine learning projects to deep learning-based image classification.

---

## Table of Contents

- [Project Objective](#project-objective)
- [Why This Project Stands Out](#why-this-project-stands-out)
- [Dataset Details](#dataset-details)
- [Project Snapshot](#project-snapshot)
- [Workflow](#workflow)
- [Preprocessing](#preprocessing)
- [Model Architecture](#model-architecture)
- [Training Setup](#training-setup)
- [Results](#results)
- [Project Visuals](#project-visuals)
- [Key Learnings](#key-learnings)
- [Tech Stack](#tech-stack)
- [Repository Structure](#repository-structure)
- [Future Scope](#future-scope)
- [Author](#author)

---

## Project Objective

The main objective of this project is to classify handwritten digit images from **0 to 9** using a deep learning model based on a **Multi-Layer Perceptron (MLP)**.

This project helps demonstrate:

- understanding of ANN-based classification
- image preprocessing for dense neural networks
- practical implementation using TensorFlow/Keras
- interpretation of model performance using plots and confusion matrix

---

## Why This Project Stands Out

Compared with earlier mini projects, this repository shows better project maturity in both **technical implementation** and **presentation quality**.

### Improvements in this project

- Transition from traditional ML to deep learning workflow
- Better GitHub repository structuring
- More polished README design and project explanation
- Visual presentation of training curves, confusion matrix, and predictions
- Clearer storytelling for recruiters and hiring managers

---

## Dataset Details

| Attribute | Information |
|----------|-------------|
| Dataset Name | MNIST Handwritten Digits |
| Source | Keras built-in dataset |
| Total Samples | 70,000 |
| Training Samples | 60,000 |
| Testing Samples | 10,000 |
| Image Size | 28 × 28 pixels |
| Classes | 10 |
| Labels | Digits 0 to 9 |

---

## Project Snapshot

| Feature | Value |
|--------|-------|
| Problem Type | Multi-class Classification |
| Domain | Computer Vision / Deep Learning |
| Dataset | MNIST |
| Model | Artificial Neural Network (MLP) |
| Framework | TensorFlow / Keras |
| Input Representation | Flattened 784-dimensional vector |
| Output | Predicted digit class |
| Accuracy | Around 97–98% |

---

## Workflow

```text
MNIST Dataset
   ↓
Data Visualization
   ↓
Normalization
   ↓
Flattening
   ↓
One-Hot Encoding
   ↓
ANN / MLP Model Building
   ↓
Training and Validation
   ↓
Model Evaluation
   ↓
Prediction and Error Analysis
```

---

## Preprocessing

Before training the model, the dataset was prepared carefully:

- Pixel values were normalized to the range **[0, 1]**
- Each 28 × 28 image was flattened into a **784-feature input vector**
- Output labels were converted into **one-hot encoded vectors**
- Separate training and testing data were used for fair evaluation

These preprocessing steps make the input suitable for dense neural network learning.

---

## Model Architecture

The model used in this project is a **Multi-Layer Perceptron (MLP)** with fully connected dense layers.

### Network Structure

- **Input Layer:** 784 neurons
- **Hidden Layer 1:** 128 neurons with ReLU activation
- **Hidden Layer 2:** 64 neurons with ReLU activation
- **Output Layer:** 10 neurons with Softmax activation

<details>
<summary><b>Why MLP was used here</b></summary>

An MLP is a strong beginner-friendly deep learning model for understanding how neural networks learn patterns from structured input data.  
In this project, image pixels are flattened into vectors, making them suitable for a dense feedforward neural network.

</details>

---

## Training Setup

- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Metric:** Accuracy
- **Epochs:** 10
- **Batch Size:** 128
- **Validation Split:** 0.1

---

## Results

- Achieved around **97–98% test accuracy**
- Training accuracy improved consistently across epochs
- Validation accuracy remained stable and strong
- Loss reduced steadily during training
- Most digits were correctly classified
- Some confusion remained among visually similar handwritten styles

> Even a simple ANN/MLP can perform very effectively on MNIST when preprocessing and model design are done properly.

---

## Project Visuals

### Accuracy Plot
<p align="center">
  <img src="Output_images/Accuracy Plot.png" alt="Training vs Validation Accuracy Plot" width="700"/>
</p>

### Loss Plot
<p align="center">
  <img src="Output_images/Loss Plot.png" alt="Training vs Validation Loss Plot" width="700"/>
</p>

### Confusion Matrix
<p align="center">
  <img src="Output_images/Confusion Matrix MNIST ANN.png" alt="Confusion Matrix for MNIST ANN Model" width="700"/>
</p>

### Visual Predictions
<p align="center">
  <img src="Output_images/Visual Predictions.png" alt="Visual Predictions of MNIST handwritten digits" width="700"/>
</p>

---

## Key Learnings

<details>
<summary><b>Click to expand key takeaways from this project</b></summary>

### Technical Learnings

- How to preprocess image data for dense neural networks
- How to design and train an MLP for multi-class classification
- How to interpret accuracy, loss curves, and confusion matrix

### Presentation Learnings

- Improved project structuring on GitHub
- Better README design with visuals and sections
- Clearer storytelling for recruiters and reviewers

</details>

---

## Tech Stack

- **Language:** Python
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
- **Framework:** TensorFlow / Keras
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

## Future Scope

This project can be extended further by:

- implementing a **Convolutional Neural Network (CNN)**
- adding dropout and regularization
- performing hyperparameter tuning
- comparing MLP vs CNN performance
- deploying the model as a simple web app for digit recognition

---

## Author

**Adiratna Kamble**  
Aspiring Data Scientist | Machine Learning & Deep Learning Enthusiast

<p>
  <a href="https://www.linkedin.com/in/adiratna-kamble">
    <img src="https://img.shields.io/badge/LinkedIn-Adiratna%20Kamble-blue?style=for-the-badge&logo=linkedin" />
  </a>
</p>
