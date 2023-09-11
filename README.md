# Income Classification Project

## Overview

This project aims to classify whether a person is earning over 50k or not based on various features. We will use classification and semi-supervised learning techniques on the UCI Machine Learning Repository dataset. The goal is to build models to predict a person's income level accurately.

## Dataset

We are using the UCI Machine Learning Repository dataset, which contains information about individuals and their income levels. The dataset has the following features:

- `Age`: Age of the individual.
- `Education Level`: The highest level of education completed.
- `Occupation`: Type of occupation.
- `Marital Status`: Marital status of the individual.
- `Race`: Race of the individual.
- ...

### Target Variable

- `Income`: Contains values '<=50k' or '>50k', indicating whether a person earns above or below 50k.

## Pre-processing

### Data Procuring

The dataset was obtained from the UCI Machine Learning Repository. It was loaded using Python, and an initial exploration was conducted to understand its structure.

### Data Cleaning

We performed data cleaning to handle missing values and outliers. Additionally, categorical variables were encoded using techniques such as one-hot encoding.

### Feature Selection

After a careful analysis, we selected `Age`, `Education Level`, `Occupation`, `Marital Status`, `Race`, and other relevant features for classification.

### Train-Test Split

The dataset was split into training and testing sets with an 80% training and 20% testing ratio.

## Classification Algorithms

We implemented two classification algorithms for this project:

1. **Logistic Regression**:
   - Logistic regression is a popular classification algorithm that models the probability of a binary outcome.

2. **Random Forest Classifier**:
   - Random Forest is an ensemble learning method that uses multiple decision trees to make predictions.

## Semi-Supervised Learning

We also explored semi-supervised learning using the `LabelPropagation` algorithm. Semi-supervised learning leverages both labeled and unlabeled data to improve classification performance.

## Conclusion

In conclusion, we have successfully applied classification and semi-supervised learning techniques to predict income levels. 
