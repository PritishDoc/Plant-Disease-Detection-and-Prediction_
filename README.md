# Plant Disease Detection and Prediction

![pexels-hiwatalaei-2364633](https://github.com/PritishDoc/Plant-Disease-Detection-and-Prediction_/assets/141579651/b2fd1d0a-35ea-49dc-b9d2-79218f831de7)

## Overview

This project is a machine learning application designed to predict plant diseases from images using a Convolutional Neural Network (CNN). The goal is to help farmers and agriculturists quickly identify diseases in their crops and take appropriate action to mitigate losses.

## Features

- **Automated Disease Detection**: Upload an image of a plant leaf to receive an immediate diagnosis.
- **User-friendly Interface**: Easy-to-use web interface for uploading images and viewing predictions.
- **Accurate Predictions**: The model is trained on a comprehensive dataset to ensure high accuracy.

## Dataset

The dataset consists of images of plant leaves categorized by disease type. It is divided into training and testing sets to evaluate the model's performance.
Here is the link of the dataset:[text](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)

## Model Architecture

The CNN model is built with the following layers:

- **Convolutional Layers**: For feature extraction from images.
- **Pooling Layers**: For reducing the dimensionality of the feature maps.
- **Fully Connected Layers**: For classification.
- **Softmax Layer**: For outputting disease probabilities.

## Installation

Follow these steps to set up the project locally:

### Prerequisites

- Python 3.7+
- TensorFlow 2.0+
- Flask
- OpenCV

### Clone the Repository

```bash
git clone https://github.com/your-username/plant-disease-detection.git
cd plant-disease-detection
