## Face Mask Detection using CNN | TensorFlow

This project detects whether a person is wearing a mask or not using a Convolutional Neural Network (CNN).
The model is trained on a face mask dataset and achieves 98%+ accuracy, making it reliable for real-world use such as monitoring systems, offices, public places, and safety automation.

## Project Features

Deep Learning model using TensorFlow + Keras

Binary Classification:
✔ With Mask
❌ Without Mask

Training accuracy: 99%

Validation accuracy: 98%+

Real-time prediction on custom images

Clean and simple architecture

Easy to run on Google Colab

## Dataset Used

The dataset contains two categories:

with_mask

without_mask


Dataset Link (Public):
https://github.com/prajnasb/observations/tree/master/experiements/data

## Model Architecture

CNN Layers

MaxPooling

Dropout

Dense Layers

Sigmoid output for binary classification


Loss Function:

binary_crossentropy

Optimizer:

Adam (lr = 0.0001)

## Model Performance

Metric	Score

Training Accuracy	~99%
Validation Accuracy	~98%
Validation Loss	Low & Stable


The model generalizes well without overfitting.
