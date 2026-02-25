🥔 Project Overview

This project implements a Convolutional Neural Network (CNN) built entirely from scratch to classify potato leaf diseases.

Unlike many image classification projects, this model does not use pre-trained architectures or transfer learning.
It covers the complete deep learning pipeline including:

Data preprocessing

Data augmentation

Model training

Model evaluation

Model versioning

🎯 Problem Statement

The objective is to classify potato leaf images into the following categories:

Early Blight

Late Blight

Healthy

The goal is to design and evaluate a custom CNN architecture capable of accurately identifying disease classes from raw image inputs.

🧠 Model Architecture

The neural network architecture includes:

Convolutional layers

ReLU activation functions

MaxPooling layers

Flatten layer

Fully connected (Dense) layers

Softmax output layer

The model was developed from scratch without leveraging any pre-trained networks.

🔄 Data Preparation & Augmentation

To improve generalization and reduce overfitting, the following preprocessing techniques were applied:

Image resizing

Pixel normalization

Rotation

Zoom

Horizontal flipping

Shearing

Validation split

These augmentation techniques helped the model learn more robust features from limited training data.

📊 Model Training & Evaluation

Loss Function: Categorical Crossentropy
Optimizer: Adam
Evaluation Metric: Accuracy

Training and validation accuracy were monitored across epochs to evaluate performance and detect overfitting.
