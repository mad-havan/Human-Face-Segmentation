## Human Face Segmentation Model
# Overview
This repository contains the implementation of a human face segmentation model. The model was trained on a dataset comprising 100 images, and various data augmentation techniques were applied to enhance the training set size. The augmentation methods include horizontal flipping, coarse dropout, random brightness, and random contrast adjustments.

# Model Architecture
The segmentation model employs a Convolutional Block Attention Mechanism and utilizes a UNET architecture with ResNet50 as the encoder. The combination of these components allows for effective feature extraction and segmentation performance.

# Evaluation Metrics
Upon testing the model with the provided test dataset, the following evaluation metrics were obtained:

Accuracy: 0.96163
F1 Score: 0.92083
Jaccard Index: 0.86558
Recall: 0.95575
Precision: 0.90659
These metrics reflect the model's performance in terms of accuracy, precision, recall, and overall segmentation quality.

# Training Process
The training process involved the augmentation of the dataset, model training with appropriate hyperparameters, and continuous refinement to achieve optimal performance.

# Usage
To use the model, follow the instructions in the provided code. Ensure that dependencies are installed, and make use of pre-trained weights available in drive

# Results
Feel free to explore the results directory for visualizations, model predictions, and any other relevant outcome data.

Google Drive Link : https://drive.google.com/drive/folders/1uZ3lE9qYlMUxSKpwzxjqgG6lo41kZNf0?usp=sharing
