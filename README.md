# PCA-Dimensionality-Reduction-Analysis
This project focuses on dimensionality reduction in datasets and improving machine learning performance using Principal Component Analysis (PCA) techniques.

# PCA & Dimensionality Reduction Analysis

## Overview
This project demonstrates the application of **Principal Component Analysis (PCA)** for dimensionality reduction on various datasets, including Body Performance and Adult Census Income data. The primary goal is to address the "Curse of Dimensionality" by reducing the number of features while retaining the maximum amount of variance/information, thereby optimizing machine learning model performance and training time.

## Project Structure
* **Data Preprocessing:** * Handling missing values (imputation).
    * Encoding categorical variables (Label Encoding).
    * Feature Scaling using `StandardScaler` to normalize data distributions.
* **PCA Implementation:** * Applying PCA to reduce high-dimensional data into principal components.
    * Analysis of explained variance ratios.
* **Visualization:** * Plotting cumulative explained variance to determine the optimal number of components.
* **Modeling:** * Implementing algorithms like Logistic Regression on both original and PCA-transformed data to compare performance.

## Files
* `PCA.ipynb` / `pca.ipynb`: Jupyter Notebooks containing the PCA logic, visualizations, and Turkish explanations of dimensionality reduction concepts.
* `adult.ipynb`: Analysis of the Adult Census Income dataset using PCA and Logistic Regression.
* `bodyPerformance.csv`: Dataset containing body performance metrics.
* `adult.csv`: Census income dataset.

## Installation & Requirements
To run the notebooks, you need Python installed along with the following libraries:

```bash
pip install pandas numpy scikit-learn matplotlib
