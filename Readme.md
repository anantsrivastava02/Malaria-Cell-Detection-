# CNN Malarial Cell Detection
## Overview
This project demonstrates the detection of malarial cells using Convolutional Neural Networks (CNN) and Multi-Layer Perceptron (MLP) models. The models are built using the Keras library and leverage various feature engineering techniques such as pooling, striding, and convolution.

## Table of Contents:
.Introduction
.Features
.Installation
.Usage
.Dataset
.Model Architecture
.Results
.Contributing
.License
.Introduction
Malaria is a life-threatening disease caused by parasites transmitted to humans through the bites of infected mosquitoes. Early and accurate detection of malarial cells is crucial for effective treatment. This project aims to build and compare CNN and MLP models for detecting malarial cells from microscopic images.

Features
CNN Model: Utilizes convolutional layers, pooling, and striding for feature extraction.
MLP Model: Applies feature engineering techniques to create a robust MLP model.
Keras Integration: Built using the Keras library for easy model creation and training.
Data Preprocessing: Includes data augmentation and normalization for improved model performance.
Installation

## Model Architecture
CNN Model
Convolutional Layers: Extract features from input images.
Pooling Layers: Downsample feature maps.
Fully Connected Layers: Perform classification based on extracted features.
MLP Model
Feature Engineering: Utilizes pooling and striding techniques.
Fully Connected Layers: Classify features into healthy or infected cells.
Results
The results of the model training and evaluation will be displayed in the console output and saved as reports in the results directory. Metrics include accuracy, precision, recall, and F1-score.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure that your code follows the project's coding standards and includes appropriate tests.

## Fork the Project
Create your Feature Branch (git checkout -b feature/your-feature)
Commit your Changes (git commit -m 'Add some feature')
Push to the Branch (git push origin feature/your-feature)
Open a Pull Request
## License
This project is licensed under the Apache License - see the LICENSE file for details.
