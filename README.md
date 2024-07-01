# Plant Disease Detection and Prediction

![pexels-hiwatalaei-2364633](https://github.com/PritishDoc/Plant-Disease-Detection-and-Prediction_/assets/141579651/b2fd1d0a-35ea-49dc-b9d2-79218f831de7)

## Overview

This project is a machine learning application designed to predict plant diseases from images using a Convolutional Neural Network (CNN). The goal is to help farmers and agriculturists quickly identify diseases in their crops and take appropriate action to mitigate losses.

## Features

- **Automated Disease Detection**: Upload an image of a plant leaf to receive an immediate diagnosis.
- **User-friendly Interface**: Easy-to-use web interface for uploading images and viewing predictions.
- **Accurate Predictions**: The model is trained on a comprehensive dataset to ensure high accuracy.

## Dataset

The dataset consists of 80K RGB images of plant leaves categorized by disease type. It is divided into training and testing sets to evaluate the model's performance.
The training set consists of 70,292 RGB images, representing 80% of the dataset, while the test set comprises 17,573 RGB images, making up the remaining 20%.
Here is the link of the dataset: [Tap Here](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)

![44](https://github.com/PritishDoc/Plant-Disease-Detection-and-Prediction_/assets/141579651/ea98c981-bb06-4a5b-a2c2-92780461780f)
## These are the image pre process steps 
![alt text](<Screenshot 2024-06-02 182010.png>)

## Model Architecture


The CNN model is built with the following layers:
![alt text](1-s2.0-S1574954121000807-ga1_lrg.jpg)
- **Convolutional Layers**: For feature extraction from images.
- **Pooling Layers**: For reducing the dimensionality of the feature maps.
- **Softmax Layer**: For outputting disease probabilities.
- **Ful!ly Connected Layers**: For classification.
![alt text](1695400757616.png)
### Graph of the Model Training and Model Loss
For our model training process, I employed the Adam optimization strategy, which is well known for its efficiency and smoother convergence when compared to alternative approaches. Ten training epochs were used to train the model, which led to increasing accuracy and decreasing loss functions on each run. 22,294 photos total from our collection were split into classes representing healthy and ill plant leaves. Positive trends were shown during the validation and training phases. Training and validation losses decreased as training and validation accuracy, as seen in Figures. These findings show how well the model learned from the data.
# Model Loss Graph
![12](https://github.com/PritishDoc/Plant-Disease-Detection-and-Prediction_/assets/141579651/e305cc95-e179-4c24-8d97-2f8d2276e3a1)
# Model Accuracy Graph

![output](https://github.com/PritishDoc/Plant-Disease-Detection-and-Prediction_/assets/141579651/71fde424-2996-4cf4-bd03-86c702f89da5)

# These are the sample output screenshot of the model
![alt text](<Screenshot 2024-06-03 090119.png>)![alt text](<Screenshot 2024-06-03 055103.png>)

![alt text](<Screenshot 2024-06-03 055747.png>)![alt text](<Screenshot 2024-06-03 055318.png>)

![alt text](<Screenshot 2024-06-03 054733.png>)![alt text](<Screenshot 2024-06-03 054953.png>)

## Installation

Follow these steps to set up the project locally:
 
### Prerequisites

- Python 3.7+
- TensorFlow 2.0+
- Flask
- OpenCV

### Clone the Repository

```bash
git clone https://github.com/PritishDoc/plant-disease-detection.git
cd plant-disease-detection
