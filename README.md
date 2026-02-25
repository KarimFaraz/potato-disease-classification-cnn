**Project Overview
**

This project implements a Convolutional Neural Network (CNN) built from scratch to classify potato leaf diseases.

The model is designed without using pre-trained architectures. It includes complete data preprocessing, augmentation, training, evaluation, and model versioning.


**Problem Statement
**

To classify potato leaf images into categories such as:

Early Blight

Late Blight

Healthy

The objective is to build a CNN architecture from scratch and evaluate its performance.


**Model Architecture
**

The model includes:

Convolutional layers

ReLU activation functions

MaxPooling layers

Flatten layer

Fully connected dense layers

Softmax output layer

No transfer learning or pre-trained neural networks were used.


**Data Preparation & Augmentation
**

To improve generalization and reduce overfitting, the following preprocessing steps were applied:

Image resizing

Pixel normalization

Rotation

Zoom

Horizontal flipping

Shearing

Validation split

Model Training & Evaluation


Loss Function: Categorical Crossentropy

Optimizer: Adam

Evaluation Metric: Accuracy
Training and validation accuracy were tracked across epochs.
