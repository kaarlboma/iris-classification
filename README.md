# Iris Dataset Classification Analysis

Machine Learning analysis of various models on the classic Iris Dataset.

## Overview

In this Jupyter Notebook, I used exploratory data analysis to understand the Iris Dataset further before benchmarking the performance of various machine learning models. I wanted to see how different ML models stood up to one another in this classification test.

## Data Visualization

- Pairplots:  To see the scatterplots of various features
- Boxplots: To identify outliers and spread
- Violin Plots: To see the distribution of various features and its density
- Heatmaps: To see correlation between various features, paired with correlation matrix

## ML Models used (+ avg. accuracy)

All models were tested with 5-fold cross validation, with their scores averaged.

- Logistic Regression: 96%
- KNN: 96%
- Gaussian Naive Bayes: 95.33%
- SVC: 93.33%
- SVM with polynomial kernel and degree 3: 92.67%
- SVM with rbf kernel: 96.67%
- Decision Tree: 96%
