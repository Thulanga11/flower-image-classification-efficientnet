# flower-image-classification-efficientnet

# Flower Image Classification using EfficientNet (Transfer Learning)

## Project Overview
This project focuses on classifying flower images into multiple categories using **EfficientNet** with **transfer learning**.  
It was implemented as a **guided learning project** to understand the complete deep learning workflow for image classification.

## Dataset
- Source: Kaggle Flowers Dataset
- Link: https://www.kaggle.com/datasets/imsparsh/flowers-dataset
- Classes: Daisy, Dandelion, Rose, Sunflower, Tulip
- Dataset downloaded using Kaggle API

## Learning Objectives
- Understand image classification pipelines
- Apply transfer learning using EfficientNet
- Perform data augmentation for better generalization
- Evaluate model performance on unseen data

## Project Flow
1. Loading the dataset using an API token  
2. Visualizing sample images  
3. Applying data augmentation  
4. Splitting the dataset into training and testing sets  
5. Building and training an EfficientNet-based model  
6. Model prediction and evaluation  

## Model Architecture
- Base Model: EfficientNetB0 (Pre-trained on ImageNet)
- Feature extractor layers frozen
- Custom fully connected classification head added
- Optimizer: Adam
- Loss Function: Sparse Categorical Cross-Entropy

## Results
The trained model achieves reasonable accuracy in classifying flower images, demonstrating the effectiveness of transfer learning for image-based tasks.
(⚠️ Data augmentation was applied before the train-test split, which may introduce data leakage.)

## Learning Source
This project was developed by following a **YouTube tutorial** as part of self-learning and skill development in Machine Learning and Deep Learning.

## ⚠️ Note
This repository is intended for **learning and practice purposes** and is not claimed as an original research contribution.
