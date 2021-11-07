# MNIST_Classification_using_CNN

The aim of this project is to detect the handwritten digit from MNIST Dataset and write an algorithm that detects which digit is written. Since there are only 10 digits (0, 1, 2, 3, 4, 5, 6, 7, 8, 9), this is a classification problem with 10 classes.

## Problem Statement

The problem we've chosen is referred to as the "Hello World" of deep learning. The goal is to write an algorithm that detects and classifies which digit is written.
In this project, we make use of Convolutional Neural Network (CNN) for the classification model.


## Project Description:

Major tasks performed:
* Preperation and preprocessing of image dataset
* Creating the model and training it using verious combinations of hyper-parameters to find the optimal combination using tensorboard
* Testing and plotting results of the optimal model

## Dataset

The dataset is called MNIST and refers to handwritten digit recognition. More details can be found on Yann LeCun's website (Director of AI Research, Facebook). He is one of the pioneers of what we've been talking about and of more complex approaches that are widely used today, such as covolutional neural networks (CNNs).

The dataset provides 70,000 images (28x28 pixels) of handwritten digits (1 digit per image).

## Project Solutions

### 1: Hyper parameter tuning:

Results:
![alt text](https://github.com/sreebink/MNIST_Classification_using_CNN/blob/bdcd1e4d9d77063a07bebdc1a788ef3c191baf64/assets/Tuning_Results.JPG)

The CNN model performed the best when hyperparameter Filter Size = 5 and Optimizer = Adaptive Moment Estimation (adam)

### 2: Testing of final model

Results:
Accuracy of slightly greater than 99%

