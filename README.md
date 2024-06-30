# Handwritten Digits Classification Using Neural Networks

This repository contains a project for classifying handwritten digits using neural networks. The project involves two models: one with 2 hidden layers and another with 1 hidden layer. The dataset used for training and testing the models is the MNIST dataset, which is available in Keras.

## Project Overview

### Models

1. **Model with 2 Hidden Layers:**
   - Architecture: Input Layer -> Hidden Layer 1 -> Hidden Layer 2 -> Output Layer
   - Activation Functions: ReLU for hidden layers, Softmax for the output layer

2. **Model with 1 Hidden Layer:**
   - Architecture: Input Layer -> Hidden Layer -> Output Layer
   - Activation Functions: ReLU for the hidden layer, Sigmoid for the output layer

### Data Preprocessing

- **Scaling:** The input data was scaled to a range of 0 to 1.
- **One-Hot Encoding:** The output labels were converted to one-hot encoded form to be used with categorical cross-entropy loss.

### Activation Methods

- **Hidden Layers:** ReLU (Rectified Linear Unit)
- **Output Layer:** Softmax and sigmoid

### Loss Function

- **Categorical Cross-Entropy Loss:** Used to measure the performance of the classification models.

### Results

- **Accuracy:** The models achieved an accuracy ranging from 97.23% to 99.66%.

![Neural Network For Handwritten Digits Classification](https://github.com/khyatig0206/Handwritten_digits_classification/assets/160642295/3465dbf4-c580-48d8-8690-41ab45ed4894)


You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
