# Fine-Grained Image Classification with PyTorch and GoogLeNet

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/rayaneghilene/Fine_Grain_Classification/blob/main/LICENSE)

## Overview

This repository contains code and resources for fine-grained image classification using PyTorch and the GoogLeNet (Inception) model. Fine-grained image classification is the task of categorizing images into fine-grained classes, often with subtle differences. In this project, we demonstrate how to fine-tune a pre-trained GoogLeNet model on a custom dataset and make predictions on new images.

## Features

- Fine-tuning a pre-trained GoogLeNet model on a custom dataset.
- Image preprocessing and data augmentation techniques.
- Testing the model on custom images.
- Demonstrations of PyTorch best practices for deep learning.

## Getting Started

### Prerequisites

- Python 3.10.8
- PyTorch
- torchvision
- Pillow (PIL)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/rayaneghilene/Fine_Grain_Classification.git
   cd Fine_Grain_Classification
   ```

### Usage
1. Data Preparation: Prepare your custom dataset. You can use the provided Fashion MNIST dataset as a starting point.

2. Fine-Tuning: Fine-tune the pre-trained GoogLeNet model on your dataset by running fine_tune_googlenet.py. Modify the code to fit your dataset and requirements.

3. Testing: Test the model on your custom images by following the instructions in the testing section. Use the pre-trained model for inference.

4. Adjust Hyperparameters: Experiment with hyperparameters, data augmentation techniques, and learning rates to optimize your model's performance.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Author
Rayane GHILENE - rayane.ghilene@ensea.fr
