# Breast Cancer Neural Network Model

## Overview
This project trains a feedforward neural network model to identify breast cancer using the Breast Cancer Wisconsin dataset. Deep learning tools allow the model to perform accurate classification.

## Features
- **Data:** The Breast Cancer Wisconsin Dataset includes 30 numeric features of breast cell images. Each breast cell in the dataset has a target label of 0 (Malignant) or 1 (Benign). The data is standardized to ensure equal feature importance.
- **Neural Network:** A multi-layer perceptron with a 30-layer input layer and a 15-layer hidden layer is used. A sigmoid function is used in the output layer for binary classification. Early stopping is also used to prevent overfitting.
- **Results:** The project uses matplotlib to display training/validation accuracy and loss over 50 epochs.

## Installation
1. Clone the repository: ```git clone https://github.com/hyao03/Breast_Cancer_NN_Project```
2. Install dependencies: ```pip install -r requirements.txt```
3. Train the model: ```python NNproject.py```

## License
MIT


