# Binary Digit Classifier using MLP

This project implements a Multi-Layer Perceptron (MLP) from scratch for binary classification of handwritten digits using the MNIST dataset. The goal is to classify images that contain only two specific digits (e.g., 1 and 5) into their corresponding class labels (0 or 1).

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

Handwritten digit recognition is a classic problem in machine learning. This project focuses on building a simple yet effective MLP model to classify images from the MNIST dataset. By limiting the classification to two digits, we can evaluate the model's performance in a binary classification context.

## Features

- **MLP Implementation:** Custom implementation of a Multi-Layer Perceptron.
- **Binary Classification:** Classifies images of two handwritten digits.
- **Data Visualization:** Visualizes the training process and results.

## Technologies Used

- Python
- NumPy
- Matplotlib
- Keras
- Seaborn
- scikit-learn
- Jupyter Notebook

## Dataset

This project utilizes the MNIST dataset, a collection of 28x28 pixel grayscale images of handwritten digits (0-9). The dataset can be accessed [here](http://yann.lecun.com/exdb/mnist/).

## Installation

To set up the project, clone the repository and install the required packages:

```bash
git clone https://github.com/yourusername/mlp_binary_digit_classifier.git
cd mlp_binary_digit_classifier
pip install numpy matplotlib keras seaborn scikit-learn
