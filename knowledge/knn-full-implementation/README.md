# K-Nearest Neighbors Full Implementation

## Overview
This repository consolidates three distinct implementations of the K-Nearest Neighbors (KNN) algorithm, each focusing on different aspects and scenarios.

## KNN from scratch
This implementation centers on the KNN algorithm applied to the Iris Dataset, offering insights into its functionality from scratch.

### Dataset Details:

- Dataset: Iris Dataset
- Observations: 150
- Input Variables: 4 (Sepal length, Sepal width, Petal length, Petal width)
- Output Variable: Class (Species of Iris)

### Key Features:

- Implementation of the KNN algorithm from scratch.
- Calculation function for test values.
- Included Manhattan Distance Function.

## KNN Basic
A comprehensive implementation of KNN across six distinct scenarios, utilizing three diverse datasets.

### Datasets:

- iris_1D: Standard iris flower dataset.
- iris_2D: Two-feature iris flower dataset.
- iris_2D_mm: Two-feature iris flower dataset with varying ranges.

### Six Cases:

- KNN with iris_1D dataset.
- KNN with iris_2D dataset.
- KNN with iris_2D dataset featuring differences in scaling.
- KNN with iris_2D dataset employing normalization.
- KNN with bag-of-word implementation.
- KNN with TF-IDF transformation.

## KNN Extended
- An extended version of the KNN algorithm applied to various datasets for diverse predictive tasks.

### Included Implementations:

- Iris Dataset KNN: Prediction of flower species based on 4 features.
- Penguins Dataset KNN: Prediction of penguin species based on 6 features.
- Iris Dataset KNN - Weighted Distances: Demonstrating importance of weighted distances.
- Text Classification using KNN Pipeline: Application of KNN for text classification.
- Cruise Ship Info Dataset KNN vs Linear Regression: Comparison of KNN and linear regression for predicting cruise ship crew size.

### About K-Nearest Neighbors (KNN)
- KNN is a simple yet powerful algorithm used for classification and regression tasks. It operates by finding the 'k' nearest data points in the training dataset to the input data point and then making predictions based on the majority class (for classification) or the average (for regression) of these neighbors.

## Repository Contents
- Code for KNN implementation across various scenarios.
- Datasets used for experimentation.
- Documentation and explanations for each case.

Feel free to explore the code and datasets provided to gain insights into the implementation and behavior of the KNN algorithm under different conditions.

This project is licensed under the MIT License. See the LICENSE file for details.
