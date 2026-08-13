# Diabetes Risk Prediction

This project analyzes health-related factors associated with diabetes risk using the **CDC Behavioral Risk Factor Surveillance System (BRFSS) 2015** dataset.
The project applies statistical analysis, regression, machine learning, regularization, PCA, and clustering techniques to explore patterns related to diabetes risk.

## Project Overview

The main goal of this project is to investigate which health and demographic characteristics are associated with diabetes and to evaluate different machine learning approaches for predicting diabetes risk.
The original diabetes outcome was converted into a binary variable:

* **0** – No diabetes
* **1** – Diabetes or prediabetes

Because the original dataset is imbalanced, the training data was balanced before applying the machine learning models.

## Notebooks

The analysis is organized into four Jupyter notebooks:

1. **01 – Data Wrangling and Exploratory Data Analysis**

   * Data cleaning and preparation
   * Descriptive statistics
   * Exploratory analysis of health and demographic variables
   * Visualization of relationships with diabetes risk

2. **02 – Statistical Inference and Regression**

   * Hypothesis testing
   * Chi-square tests
   * t-tests
   * Regression analysis

3. **03 – Model Selection and Regularization**

   * Logistic Regression
   * Decision Tree
   * Random Forest
   * Model comparison
   * L1 (Lasso), L2 (Ridge), and Elastic Net regularization

4. **04 – PCA and Clustering**

   * Principal Component Analysis (PCA)
   * Explained variance analysis
   * K-Means clustering
   * Elbow method

## Machine Learning

Several classification models were evaluated to identify patterns associated with diabetes risk. Model performance was compared using:

* Accuracy
* Precision
* Recall
* F1-score

Because this is a health-related prediction problem, **recall is particularly important**, since missing individuals who may be at risk can be more concerning than incorrectly identifying someone as at risk.

## Dataset

The project uses the **CDC BRFSS 2015 diabetes health indicators dataset**.

The original dataset is **not included in this repository**. The CSV file was intentionally excluded from GitHub using `.gitignore`.

## Important Limitation

One important limitation of this dataset is that it does not include a direct **blood glucose measurement**. Blood glucose is one of the main clinical measurements used when diagnosing diabetes and prediabetes.

Therefore, the models in this project should be interpreted as identifying **patterns and risk factors associated with diabetes**, rather than providing a clinical diagnosis.

## Tools and Technologies

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy
* Git and GitHub



