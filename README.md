# Insurance ML – Linear Algebra & Data Protection Project

## Project Overview
This project demonstrates practical applications of **linear algebra** in machine learning using real-world insurance data. The goal is to solve multiple business tasks including customer similarity analysis, classification, regression, and personal data protection, while preserving model quality.

The project emphasizes the mathematical foundations behind machine learning models and shows how data transformations impact predictions.

## Objective
The main objectives of this project are to:
- Identify customers similar to a given individual for marketing purposes.
- Predict whether a customer is likely to receive insurance benefits.
- Estimate the number of insurance benefits a customer may receive using linear regression.
- Protect sensitive personal data through feature transformation without degrading model performance.

## Dataset
The dataset used in this project:
- `insurance_us.csv`

Features:
- Gender
- Age
- Salary
- Number of family members

Target variable:
- Number of insurance benefits received over the last five years

## Data Preparation
- Loaded and inspected the dataset for missing values and anomalies.
- Verified data consistency and feature distributions.
- Ensured data suitability for machine learning tasks.

## Task 1: Customer Similarity
- Implemented a similarity-based approach to identify customers with profiles close to a selected individual.
- Demonstrated how distance-based methods can support targeted marketing strategies.

## Task 2: Insurance Benefit Classification
- Built a model to predict whether a customer is likely to receive insurance benefits.
- Compared the performance of a trained model against a dummy baseline.
- Analyzed scenarios where a trained model may perform better or worse than a baseline model.

## Task 3: Insurance Benefit Regression
- Trained a linear regression model to predict the number of insurance benefits.
- Evaluated model performance and interpreted results through the lens of linear algebra.

## Task 4: Data Protection via Linear Transformation
- Developed a data transformation algorithm to protect personal information.
- Applied linear algebra techniques to mask sensitive data.
- Demonstrated that the transformation preserves model performance while preventing data recovery.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Linear Algebra concepts
- Jupyter Notebook

## Business Value
This project shows the ability to:
- Apply linear algebra concepts to real machine learning problems.
- Build interpretable models for classification and regression.
- Compare trained models with baseline approaches.
- Protect sensitive customer data without compromising predictive quality.

The approach is directly applicable to insurance, finance, and regulated industries where data privacy and model reliability are critical.
