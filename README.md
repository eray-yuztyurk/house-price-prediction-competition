# House Price Prediction - Competition

## Overview

This repository contains a machine learning project focused on predicting house prices based on various features of residential homes in Ames, Iowa. The project utilizes a dataset comprising 79 explanatory variables, including both numerical and categorical features, with the target variable being the sale price of the properties. The ultimate goal is to develop a robust predictive model to estimate house prices accurately.

---
<p align="center">
    <img width="600" height="600" alt="house-price-prediction" src="https://github.com/user-attachments/assets/900a3eed-be14-4c13-828a-cb4e07ec86b3" />
</p>


----

## Business Problem

The aim of this project is to implement a machine learning solution that can predict house prices based on the characteristics of individual properties. This predictive model can be valuable for real estate professionals, homeowners, and investors in making informed decisions regarding property transactions.

## Dataset

The dataset consists of 1460 observations with 38 numerical variables and 43 categorical variables. It includes features such as LotFrontage, LotArea, OverallQual, OverallCond, YearBuilt, and numerous others, providing comprehensive insights into the properties' attributes.

## Steps

1. **Exploratory Data Analysis (EDA):**
    - **Reading and Merging Datasets:** The training and testing datasets are read and merged for comprehensive analysis.
    - **Identifying Variables:** Numerical and categorical variables are identified for further analysis.
    - **Adjustments:** Necessary adjustments, such as handling missing values and outliers, are made.
    - **Distribution Analysis:** The distribution of numerical and categorical variables is examined.
    - **Relationship Analysis:** The relationship between categorical variables and the target variable (SalePrice) is explored.
    - **Outlier Detection:** Any outliers in the data are identified and addressed.
    - **Missing Data Investigation:** Missing observations are investigated and handled appropriately.

2. **Feature Engineering:**
    - **Handling Missing and Outlier Observations:** Necessary operations are performed to handle missing and outlier observations.
    - **Rare Encoder:** A rare encoder is applied to handle infrequent categorical values.
    - **Creating New Variables:** New variables are created to enhance the predictive power of the model.
    - **Encoding Operations:** Categorical variables are encoded for model compatibility.

3. **Model Building:**
    - **Data Splitting:** The dataset is split into training and testing sets.
    - **Model Development:** Various machine learning models are built using the training data, and their performance is evaluated.
    - **Hyperparameter Optimization:** Hyperparameters of the models are optimized to enhance performance.
    - **Variable Importance Examination:** The importance of variables in predicting house prices is analyzed to gain insights into the model's decision-making process.
