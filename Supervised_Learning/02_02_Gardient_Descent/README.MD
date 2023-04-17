# Outline

1. [Gradient Descent - Logistic Regression](#gradient-descent---logistic-regression)
    - [Introduction](#introduction)
    - [Algorithm](#algorithm)
        - [Hypothesis Function](#hypothesis-function)
        - [Binary Cross Entropy Loss Function](#binary-cross-entropy-loss-function)
        - [Gradient Descent](#gradient-descent)
        - [Derivative of the Cost Function](#derivative-of-the-cost-function)
    - [Implementation](#implementation)
        - [Sigmoid function](#sigmoid-function)
        - [Cost function (cross-entropy loss)](#cost-function-cross-entropy-loss)
        - [Gradient descent](#gradient-descent-1)
        - [Feature scaling (normalization)](#feature-scaling-normalization)
        - [Logistic regression](#logistic-regression)
        - [Prediction function](#prediction-function)
        - [Model evaluation](#model-evaluation)
            - [Accuracy and confusion matrix](#accuracy-and-confusion-matrix)
            - [Cost vs Iterations plot](#cost-vs-iterations-plot)

# Data Description

The dataset used in this Jupyter Notebook is the [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)). It contains 569 samples with 30 numeric input features describing the characteristics of cell nuclei present in a digitized image of a fine needle aspirate (FNA) of a breast mass. The objective is to predict if the cancer is benign (0) or malignant (1) based on these features.
