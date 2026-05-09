# Handwritten Digit Classification on MNIST Using Artificial Neural Network (MLP)

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?style=flat-square&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Neural%20Network-red?style=flat-square&logo=keras)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=flat-square)

## Project Overview

This project focuses on classifying handwritten digits (0–9) from the MNIST dataset using an **Artificial Neural Network (MLP)** model.  
The workflow includes dataset loading, visualization, preprocessing, model building, training, evaluation, prediction, and performance analysis.

## Objective

To build an ANN-based Multi-Layer Perceptron model that can correctly classify handwritten digit images from the MNIST dataset.

## Dataset Information

- **Dataset:** MNIST Handwritten Digits
- **Source:** Keras built-in dataset
- **Total samples:** 70,000 images
- **Training samples:** 60,000
- **Testing samples:** 10,000
- **Image size:** 28 × 28 pixels
- **Classes:** 10 digits (0 to 9)

## Project Workflow

1. Import required libraries  
2. Load the MNIST dataset  
3. Visualize sample handwritten digits  
4. Preprocess the data  
5. Build the ANN (MLP) model  
6. Compile and train the model  
7. Evaluate test performance  
8. Generate predictions  
9. Visualize confusion matrix and sample outputs  

## Preprocessing Steps

- Scaled pixel values to the range [0, 1]
- Flattened each 28 × 28 image into a 784-feature vector
- Applied one-hot encoding to class labels

## Model Architecture

- **Input layer:** 784 features
- **Hidden layer 1:** 128 neurons, ReLU activation
- **Hidden layer 2:** 64 neurons, ReLU activation
- **Output layer:** 10 neurons, Softmax activation

## Training Details

- **Optimizer:** Adam
- **Loss function:** Categorical Crossentropy
- **Metric:** Accuracy
- **Epochs:** 10
- **Batch size:** 128
- **Validation split:** 0.1

## Results

- Achieved strong test accuracy of around **97–98%**
- Training and validation curves showed stable learning
- Confusion matrix showed that most digits were classified correctly
- Some misclassifications were observed for visually similar handwritten digits

## Observations

- The ANN model performed very well on the MNIST dataset
- Digit **5** appeared to be misclassified more often in some cases
- This may be due to variation in handwriting styles and similarity with other digits

## Conclusion

This project demonstrates that an **Artificial Neural Network (MLP)** can achieve high accuracy on handwritten digit classification tasks.  
It also shows the importance of preprocessing, neural network design, and evaluation techniques such as confusion matrix analysis.

## Future Improvement

A Convolutional Neural Network (CNN) can be used in the future for even better image classification performance, since CNNs are more suitable for image-based tasks.

## Tools and Libraries

- Python
- NumPy
- Matplotlib
- Seaborn
- TensorFlow / Keras
- Jupyter Notebook

## Repository Contents

- `MNIST_Artificial_Neural_Network_Handwritten_Digits_Classification.ipynb`
- `README.md`
- `requirements.txt` *(optional)*

## Author

**Adiratna Kamble**  
[LinkedIn](https://www.linkedin.com/in/adiratna-kamble)
