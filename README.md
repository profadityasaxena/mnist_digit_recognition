# MNIST Digit Recognition Project - Summary

## Overview
This project focuses on applying machine learning techniques to the **MNIST dataset**, a widely used benchmark for handwritten digit recognition. The dataset contains **60,000 training images** and **10,000 testing images**, each normalized to **28 × 28 pixels**.

## Objective
The goal is to implement and compare various machine learning algorithms to classify images of handwritten digits (0-9) accurately. The project is divided into two parts, with this phase covering the first part.

## Tools and Libraries
- **Python 3.11**
- **NumPy** (for numerical operations)
- **Matplotlib** (for visualization)
- **Scikit-learn** (for machine learning algorithms)

## Project Structure
The **part1/** folder:

- `linear_regression.py` - Implementation of linear regression
- `svm.py` - Implementation of support vector machines
- `softmax.py` - Implementation of multinomial regression
- `features.py` - Implementation of PCA (dimensionality reduction)
- `kernel.py` - Implementation of polynomial and Gaussian RBF kernels
- `main.py` - Driver file for running the implemented methods

## Dataset Handling
Data is provided in `mnist.pkl.gz` and can be loaded using `get_MNIST_data` from `utils.py`. This function returns:
- `train_x`: Feature matrix for training images
- `train_y`: Labels for training data
- `test_x`: Feature matrix for test images
- `test_y`: Labels for test images (only for evaluation)

## Implementation Guidelines
1. Run `python main.py` to load and visualize the first 20 images.
2. Implement and test machine learning models locally before submitting to the MITx online grading system.
3. Use `Scikit-learn` documentation and online resources to support the development process.

## Notes
- The `test_y` labels should only be used for model evaluation.
- Assume `NumPy` is pre-imported as `np`.
- Utilize the local machine for debugging before submitting solutions online.

