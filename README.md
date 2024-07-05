# Companion Arbiter PUFs

This repository contains the assignment for the course CS771: Introduction to Machine Learning, taken by Prof. Purushottam Kar, during 2024 Semester - II. 

## Abstract

The assignment focuses on developing a linear model for a Companion Arbiter PUF (Physically Unclonable Function) problem and experimenting with various machine learning models and hyperparameters.

## Contents

1. Mathematical derivation of a linear model
2. Python implementation of the model
3. Experimental analysis of different models and hyperparameters

## Implementation Details

The main implementation is in Python, using the following libraries:
- NumPy
- scikit-learn

The core functions implemented are:
- `my_fit`: Trains the model on the given data
- `my_map`: Maps the input challenges to the feature space

## Models Explored

1. LinearSVC
2. Logistic Regression

## Hyperparameter Analysis

The project includes an extensive analysis of various hyperparameters, including:
- Loss function (hinge vs squared hinge)
- Regularization parameter (C)
- Tolerance (tol)
- Penalty (l1 vs l2)

## Results

The best performance was achieved using Logistic Regression with an accuracy of 0.993 and training time of 1.99s.