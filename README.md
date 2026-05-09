<h1 align="center">Handwritten Digit Classification on MNIST Using Artificial Neural Network (MLP)</h1>

<p align="center">
  <b>Deep Learning mini project focused on classifying handwritten digits (0–9) using a Multi-Layer Perceptron (ANN) model.</b>
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

---

## Table of Contents

- [Project Overview](#project-overview)
- [Why This Project](#why-this-project)
- [Dataset Information](#dataset-information)
- [Project Highlights](#project-highlights)
- [Workflow](#workflow)
- [Data Preprocessing](#data-preprocessing)
- [Model Architecture](#model-architecture)
- [Training Configuration](#training-configuration)
- [Results and Insights](#results-and-insights)
- [Project Visuals](#project-visuals)
- [Tools and Libraries](#tools-and-libraries)
- [Repository Structure](#repository-structure)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## Project Overview

This project builds a handwritten digit classification system using the **MNIST dataset** and an **Artificial Neural Network (MLP)**.  
The main objective is to classify grayscale digit images into one of the ten digit classes from **0 to 9**.

This project covers the complete deep learning workflow:
- data loading
- image visualization
- preprocessing
- ANN model building
- training and validation
- prediction
- performance evaluation

---

## Why This Project

This project is an important step in progressing from traditional machine learning projects to **deep learning-based image classification**.

It demonstrates:
- understanding of neural networks for classification
- handling of image data in tabular-vector form
- practical usage of TensorFlow/Keras
- model evaluation using confusion matrix and prediction outputs

It also shows an upgrade from earlier GitHub mini projects by presenting a more structured deep learning pipeline.

---

## Dataset Information

- **Dataset Name:** MNIST Handwritten Digits
- **Source:** Keras built-in dataset
- **Total Images:** 70,000
- **Training Samples:** 60,000
- **Testing Samples:** 10,000
- **Image Dimension:** 28 × 28 pixels
- **Number of Classes:** 10
- **Target Labels:** Digits from 0 to 9

---

## Project Highlights

| Feature | Details |
|---------|---------|
| Problem Type | Multi-class Classification |
| Domain | Computer Vision / Deep Learning |
| Dataset | MNIST |
| Model Used | Artificial Neural Network (MLP) |
| Framework | TensorFlow / Keras |
| Input Form | Flattened 28 × 28 images |
| Output | Predicted digit class |
| Performance | Around 97–98% test accuracy |

---

## Workflow

```text
MNIST Dataset
     ↓
Data Visualization
     ↓
Normalization and Reshaping
     ↓
One-Hot Encoding
     ↓
ANN / MLP Model Building
     ↓
Model Training
     ↓
Evaluation on Test Data
     ↓
Prediction and Error Analysis
```

---

## Data Preprocessing

The following preprocessing steps were applied before model training:

- Pixel values were scaled to the range **[0, 1]**
- Each 28 × 28 image was flattened into a **784-dimensional input vector**
- Output labels were converted using **one-hot encoding**
- Training and testing data were prepared separately for clean model evaluation

---

## Model Architecture

The neural network used in this project is a **Multi-Layer Perceptron (MLP)** with fully connected dense layers.

### Architecture Summary

- **Input Layer:** 784 neurons
- **Hidden Layer 1:** 128 neurons with ReLU activation
- **Hidden Layer 2:** 64 neurons with ReLU activation
- **Output Layer:** 10 neurons with Softmax activation

### Learning Objective

The model learns useful pixel-level patterns from digit images and maps them to the correct digit class.

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

- The model achieved approximately **97–98% accuracy** on the test dataset.
- Training and validation behavior showed stable learning performance.
- Most handwritten digits were classified correctly.
- A few errors occurred between visually similar digits.
- This project highlights how even a basic ANN can perform strongly on a well-structured image dataset like MNIST.

---

## Project Visuals

> Add your saved output images from the `Output_images` folder here for a more attractive recruiter-facing README.

### Sample Output Sections You Can Show

- Sample handwritten digit images
- Model training accuracy/loss curves
- Confusion matrix
- Predicted vs actual digit outputs

Example image embedding format:

```markdown
<p align="center">
  <img src="Output_images/your-image-name.png" width="700"/>
</p>
```

If you want, this section can later be upgraded with your exact image file names.

---

## Tools and Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow
- Keras
- Scikit-learn
- Jupyter Notebook

---

## Repository Structure

```bash
MNIST-Artificial-Neural-Network-Handwritten-Digits-Classification/
│
├── Notebook(Python File)/
│   └── MNIST_Artificial_Neural_Network_Handwritten_Digits_Classification.ipynb
│
├── Output_images/
│   └── project output images
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## Future Improvements

This project can be improved further by:

- implementing a **Convolutional Neural Network (CNN)** for better image feature learning
- experimenting with dropout and regularization
- tuning hidden layers and neuron counts
- comparing ANN vs CNN performance on MNIST
- deploying the trained model as a simple digit prediction web app

---

## Author

**Adiratna Kamble**  
Aspiring Data Scientist | Machine Learning & Deep Learning Enthusiast

<p align="left">
  <a href="https://www.linkedin.com/in/adiratna-kamble">
    <img src="https://img.shields.io/badge/LinkedIn-Adiratna%20Kamble-blue?style=for-the-badge&logo=linkedin" />
  </a>
</p>
