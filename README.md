# MNIST Handwritten Digits Classifier

This project demonstrates a simple implementation of a Convolutional Neural Network (CNN) for classifying handwritten digits using the MNIST dataset. The notebook walks through data loading, preprocessing, model building, training, and evaluation using PyTorch.

## Dataset

The MNIST dataset contains 70,000 grayscale images of handwritten digits (0-9), each of size 28x28 pixels. It is a benchmark dataset in the field of machine learning.

## Key Features

- **Data Preprocessing**: The dataset is normalized and transformed using PyTorch's `torchvision.transforms`.
- **Model Architecture**: A simple CNN model is built using PyTorch's `torch.nn` module.
- **Training**: The model is trained using the `Adam` optimizer and `cross-entropy` loss.
- **Evaluation**: The model's performance is evaluated on the test set, and metrics like accuracy are reported.

## Installation

To run this notebook, you need Python 3.x and the following libraries:

- PyTorch
- torchvision
- NumPy
- Matplotlib

Install the required libraries using pip:

```bash
pip install -r requirements.txt
