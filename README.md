# Handwritten Digit Classification with Deep Learning Models

This project focuses on the classification of handwritten digits using various deep learning models trained on the MNIST dataset. The dataset consists of 60,000 training images and 10,000 testing images of handwritten digits (0 through 9).

## Models Overview

I have developed 8 different types of deep learning models, each with minor modifications, for classifying the handwritten digits. These models are categorized into two groups:

1. Models trained on direct input images (Images are flattened intp 1d array).
2. Models trained on reduced dimensions of input using Principal Component Analysis (PCA) technique.

### Direct Input Models

1. **1H_Sig**
   - Single hidden layer with sigmoid activation.
   - Training Accuracy: 94.46%
   - Testing Accuracy: 93.85%

2. **1H_LeakR**
   - Single hidden layer with LeakyReLU activation.
   - Training Accuracy: 98.56%
   - Testing Accuracy: 96.98%

3. **2H_Sig**
   - Two hidden layers with sigmoid activation.
   - Training Accuracy: 95.47%
   - Testing Accuracy: 95.01%

4. **2H_LeakR**
   - Two hidden layers with LeakyReLU activation.
   - Training Accuracy: 98.12%
   - Testing Accuracy: 96.63%

### Models with PCA

5. **1H_Sig_PCA**
   - Single hidden layer with sigmoid activation trained on reduced dimensions.
   - Training Accuracy: 96.90%
   - Testing Accuracy: 94.73%

6. **1H_LeakR_PCA**
   - Single hidden layer with LeakyReLU activation trained on reduced dimensions.
   - Training Accuracy: 98.97%
   - Testing Accuracy: 96.67%

7. **2H_Sig_PCA**
   - Two hidden layers with sigmoid activation trained on reduced dimensions.
   - Training Accuracy: 98.74%
   - Testing Accuracy: 96.57%

8. **2H_LeakR_PCA**
   - Two hidden layers with LeakyReLU activation trained on reduced dimensions.
   - Training Accuracy: 98.80%
   - Testing Accuracy: 96.90%

## Comparative Analysis

Based on observations, I found that models utilizing LeakyReLU activation consistently outperform those using sigmoid activation. Additionally, models trained on reduced dimensions using PCA technique demonstrate better performance compared to their counterparts trained on direct input images.

