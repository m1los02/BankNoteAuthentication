# BankNoteAuthentication

# Banknote Authentication — Logistic Regression from Scratch

This project implements **Logistic Regression from scratch** to classify whether a banknote is genuine or forged based on its physical characteristics.

## Dataset Overview

The dataset contains features extracted from images of banknotes using wavelet transforms. Each instance has the following attributes:

- **variance** of wavelet-transformed image  
- **skewness** of wavelet-transformed image  
- **kurtosis** of wavelet-transformed image  
- **entropy** of image  
- **class** *(target)*:  
  - `0` for forged  
  - `1` for authentic

The dataset is available at the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/banknote+authentication).

## Project Goal

The objective is binary classification:  
**Predict whether a banknote is genuine (1) or fake (0).**

In this project, I implemented Logistic Regression **from scratch**, focusing on:

- Sigmoid activation function  
- Gradient Descent optimization  
- Cost function (binary cross-entropy)  
- Model evaluation using accuracy, precision, recall, and F1-score

## Skills Demonstrated

- Building Logistic Regression manually (without using ML libraries)  
- Data preprocessing and visualization  
- Vectorized implementation using NumPy  
- Confusion matrix analysis  
- Understanding convergence and learning rates

## Motivation

I wanted to understand how binary classification models work under the hood. This project helped me solidify my understanding of the math behind Logistic Regression, especially gradient descent and decision boundaries.


