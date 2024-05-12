# Customer Segmentation and Classification

This repository contains a Python code for performing customer segmentation and classification using RFM (Recency, Frequency, Monetary) analysis on an online retail dataset. The code includes data preprocessing, visualization, and the implementation of various machine learning models.

## Dataset

The dataset used in this project is the "Online Retail" dataset, which contains information about online retail transactions. The dataset is loaded using the `pd.read_excel` function from the pandas library.

## Dependencies

The following Python libraries are required:

- pandas
- numpy
- random
- seaborn
- calendar
- datetime
- matplotlib
- scikit-learn

## Usage

1. Install the required dependencies
2. Run the Python script to analyze the data, train the machine learning models, and evaluate their performance.

## RFM Analysis

The code performs RFM (Recency, Frequency, Monetary) analysis on the dataset. It calculates the Recency, Frequency, and Monetary values for each customer and assigns corresponding scores.

**Customer Segmentation**: Based on the RFM scores, customers are segmented into different categories such as "Inactive Customers," "Loyal Customers," "New Customers," and more.

## Machine Learning Pipelines

The code builds machine learning pipelines for four different models:
   - Principal Component Analysis (PCA)
   - K-Means Clustering
   - K-Nearest Neighbors (KNN)
   - Random Forest Classifier
