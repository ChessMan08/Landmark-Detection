# Landmark Detection using Google Landmark Detection Dataset (GLDv2)

## Project Overview

This project involves building a deep learning model for landmark detection using the Google Landmark Detection Dataset (GLDv2). The dataset contains over 5 million images with more than 200,000 unique landmarks. The model is trained to accurately identify and categorize landmarks across diverse images.

## Table of Contents

- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Installation](#installation)

## Dataset

The Google Landmark Detection Dataset (GLDv2) is a large-scale dataset with:
- **5 million+ images**
- **200,000+ unique landmarks**

This dataset is a benchmark for large-scale image retrieval and classification, providing a rich and diverse set of landmarks from around the world.

## Model Architecture

The model is built using state-of-the-art deep learning techniques. The architecture includes:
- **Convolutional Neural Networks (CNNs)** for feature extraction.
- **Attention mechanisms** to focus on distinctive parts of the landmarks.
- **Transfer Learning** using pre-trained models to leverage existing knowledge.

## Training

The model was trained using the following techniques:
- **Data Augmentation** to increase the variety of images and prevent overfitting.
- **Batch Normalization** for faster convergence and stable training.
- **Optimizer**: Adam optimizer was used with a learning rate scheduler.
- **Loss Function**: Categorical cross-entropy for classification tasks.

## Evaluation

The model's performance was evaluated using:
- **Accuracy**: Overall accuracy on the validation set.
- **Precision, Recall, and F1-Score**: For detailed analysis of model performance.
- **Confusion Matrix**: To visualize the classification results and errors.


## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/ChessMan08/landmark-detection.git
    ```
