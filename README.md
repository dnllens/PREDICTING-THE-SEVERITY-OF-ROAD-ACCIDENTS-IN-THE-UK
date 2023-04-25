# PREDICTING-THE-SEVERITY-OF-ROAD-ACCIDENTS-IN-THE-UK


This project aims to predict accident severity using traditional machine learning algorithms and neural networks. The dataset used in this project is derived from the UK Department for Transport, consisting of road accidents in the UK from 2005 to 2014.

## Overview

The project consists of four main parts:

1. Data Preprocessing
2. Classification using Traditional Machine Learning
3. Classification using Neural Networks
4. Model Evaluation and Comparison

### 1. Data Preprocessing

Data preprocessing involved cleaning and preparing the data for analysis. The main steps involved were:

- Data cleaning: removing duplicates, handling missing values, and correcting inconsistencies.
- Feature engineering: creating new features and transforming existing ones to improve model performance.
- Data splitting: dividing the dataset into training and testing sets.

### 2. Classification using Traditional Machine Learning

Several traditional machine learning algorithms were employed to classify accident severity into three categories: "fatal," "serious," and "slight." The classification algorithms used were:

- SGD Classifier
- Logistic Regression
- Naïve Bayes
- Random Forest
- Decision Tree
- k-Nearest Neighbour

Hyperparameters for each algorithm were optimized using grid search with cross-validation. Model performance was evaluated using confusion matrices and performance metrics, including accuracy and precision.

### 3. Classification using Neural Networks

A multi-layer perceptron (MLP) model was created for classifying accident severity. The neural network model was optimized using a grid search over various hyperparameters, including learning rate and the number of hidden layer nodes. Model performance was evaluated using confusion matrices, performance metrics, and comparison with a trivial baseline.

### 4. Model Evaluation and Comparison

The performance of traditional machine learning algorithms and the neural network model was compared based on their accuracy and precision. The Neural Network model achieved the highest performance metrics, with an accuracy of 0.78. The learning curve of the Neural Network model was also analyzed to further investigate its performance.

## Conclusion

The Neural Network model provided the most credible and accurate solution for determining accident severity. It outperformed traditional machine learning algorithms in terms of accuracy and precision, making it the best choice for predicting accident severity in this dataset.

