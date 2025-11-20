# CodeAlpha_MINST_Data
MNIST Handwritten Digit Classification Using CNN
Overview

Classify handwritten digits (0–9) from the MNIST dataset using a Convolutional Neural Network (CNN). Achieves high accuracy on test data with a simple CNN architecture.

Dataset

Source: MNIST

Images: 28x28 grayscale

Classes: 10 (digits 0–9)

Split: 60k train / 10k test

<h2> Requirements</h2>
pip install tensorflow numpy matplotlib scikit-learn

CNN Architecture

Conv2D → ReLU → MaxPooling

Conv2D → ReLU → MaxPooling

Flatten → Dense(128) → ReLU → Dense(10) → Softmax
This simple model reach accuracy of 98% at testing 
