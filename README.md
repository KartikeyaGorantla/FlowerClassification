# Convolutional Neural Network Project (Flower Classification)

This repository contains a Convolutional Neural Network (CNN) project implemented in a Jupyter Notebook (`Flowers_Classification.ipynb`). The project is designed for image classification and includes the following components:

## Table of Contents
- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Building the CNN](#building-the-cnn)
- [Training and Evaluation](#training-and-evaluation)
- [Testing](#testing)
- [Usage](#usage)

## Introduction

This project utilizes a CNN to perform image classification on a dataset of flowers. It includes the following major components:

## Data Preprocessing
The dataset is divided into training and validation sets. Data augmentation techniques are applied to the training data to enhance model generalization.

## Building the CNN
The CNN architecture is defined using TensorFlow and Keras. It consists of multiple convolutional layers, pooling layers, and fully connected layers.

## Training and Evaluation
The CNN is trained on the training data, and training progress is monitored using custom callback functions. The accuracy and loss graphs are plotted to visualize model performance.

## Testing
The trained model is saved to a file (`Flowers_final.h5`) and then loaded for testing. Images from a specified folder are classified using the saved model.

## Usage
To use this project, follow these steps:

1. Ensure you have the required libraries and dependencies installed. You can check the TensorFlow version using `print(tf.__version__)`.

2. Run the code in the Jupyter Notebook (`Flowers_Classification.ipynb`) step by step, starting from data preprocessing to training the model.

3. After training, you can test the model by providing images in the `flower_photos/single_prediction/` folder. The script will predict the flower class and display the image with the prediction.


Feel free to customize and extend this project for your own image classification tasks. Enjoy experimenting with CNNs!

