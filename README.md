﻿# CIFAR10-IMAGE-CLASSIFIER
This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset, which consists of 60,000 32x32 color images across 10 classes (e.g., airplane, automobile, bird, etc.). The model is built using TensorFlow and Keras, incorporating data preprocessing, augmentation, and advanced training techniques to achieve robust performance.

Features

Dataset: Utilizes the CIFAR-10 dataset, split into training (35,000 images), validation (15,000 images), and test (10,000 images) sets.
Preprocessing: Normalizes images using mean and standard deviation for improved model convergence.
Model Architecture: A Sequential CNN with Conv2D, MaxPooling2D, Dropout, BatchNormalization, and Dense layers, enhanced with L2 regularization.
Training: Employs data augmentation (via ImageDataGenerator), learning rate scheduling (ReduceLROnPlateau), and early stopping to prevent overfitting.
Visualization: Displays a grid of sample images with their corresponding labels using Matplotlib.
Prediction: Includes functionality to preprocess and classify new images, demonstrated with a sample prediction pipeline.

Technologies Used

Python, TensorFlow, Keras, OpenCV (cv2), NumPy, Matplotlib, Scikit-learn
GPU acceleration (Google Colab with T4 GPU)

![image](https://github.com/user-attachments/assets/cf007c85-c357-49df-8ccf-481648f70196)

