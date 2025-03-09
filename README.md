# Rice Classification using PyTorch (Tabular Classification)

## 📌 Project Overview

This project focuses on classifying different varieties of rice using tabular data and deep learning with PyTorch. The dataset consists of numerical features that describe rice grains, and a neural network model is trained to classify them accurately.

## 📂 Dataset

The dataset used in this project is sourced from Kaggle and contains various physical characteristics of rice grains:

Features:

- Area

- MajorAxisLength

- MinorAxisLength

- Eccentricity

- ConvexArea

- EquivDiameter

- Extent

- Perimeter

- Roundness

- AspectRatio

- Target Variable: Class (Rice variety, e.g., Basmati, Jasmine, Arborio, etc.)


## 🔧 Data Preprocessing

The dataset is preprocessed using Pandas and NumPy with the following steps:

- Handling missing values

- Splitting into training, validation, and test sets

## 🚀 Model Architecture

The PyTorch model is a fully connected neural network with the following structure:

- Input Layer: Matches the number of numerical features

- Hidden Layers: Multiple layers with ReLU activation

- Output Layer: Softmax activation for classification

- Loss Function: CrossEntropyLoss

- Optimizer: Adam

## 📌 Learning PyTorch through this Project

This project serves as an excellent introduction to deep learning with PyTorch for tabular classification tasks. By working through this, you will learn:

- How to preprocess tabular data for machine learning models.

- Building and training a neural network using PyTorch.

- Implementing backpropagation and optimization techniques.

- Evaluating model performance with appropriate metrics.

- Debugging and fine-tuning deep learning models.
