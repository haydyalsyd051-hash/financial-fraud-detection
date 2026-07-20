# Financial Transaction Fraud Detection

## Overview

This project focuses on detecting and classifying financial transactions into three categories:

* Fraud
* Suspicious
* Legit

The goal is to build a machine learning model capable of identifying potentially fraudulent activities while providing insights into the factors influencing transaction classification.

## Dataset

The dataset contains financial transaction records with transaction details, customer information, transaction channels, locations, and transaction status labels.

Target Classes:

* Fraud
* Suspicious
* Legit

## Project Workflow

### 1. Data Preprocessing

* Handling missing values
* Removing duplicates
* Correcting inconsistent records
* Standardizing city names, transaction categories, and channels
* Detecting and handling invalid values

### 2. Exploratory Data Analysis (EDA)

* Class distribution analysis
* Feature relationship exploration
* Statistical summaries
* Data visualization

### 3. Feature Engineering

* Encoding categorical features
* Preparing numerical features
* Creating machine-learning-ready datasets

### 4. Model Development

* Training classification models
* Hyperparameter optimization
* Model comparison and evaluation

### 5. Model Evaluation

Performance was evaluated using:

* Accuracy Score
* F1 Score
* Classification Report
* Confusion Matrix

### 6. Feature Importance Analysis

Identified the most influential features contributing to fraud detection decisions.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Results

The developed model successfully classified financial transactions into Fraud, Suspicious, and Legit categories, providing valuable insights for fraud monitoring and risk assessment.

## Project Deliverables

* Data Cleaning & Preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Machine Learning Model
* Performance Evaluation
* Visualizations & Insights
* Organized Jupyter Notebook
