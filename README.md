# # Ames House Price Prediction – Regression Analysis

---

<p align="center">
    <img width="400" alt="Ames house price prediction" src="https://github.com/user-attachments/assets/900a3eed-be14-4c13-828a-cb4e07ec86b3" />
</p>

---

## Table of Contents
- [Overview](#overview)
- [Business Motivation](#business-motivation)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Usage](#usage)
- [Results / Evaluation](#results--evaluation)
- [Technologies](#technologies)
- [License](#license)

---

<table align="center">
  <tr>
    <!-- LEFT: TABLE OF CONTENTS -->
    <td align="left" width="50%" style="vertical-align: top;">
      <h3>📑 Table of Contents</h3>
      <ul>
        <li><a href="#overview">Overview</a></li>
        <li><a href="#business-motivation">Business Motivation</a></li>
        <li><a href="#dataset">Dataset</a></li>
        <li><a href="#project-workflow">Project Workflow</a></li>
        <li><a href="#usage">Usage</a></li>
        <li><a href="#results--evaluation">Results / Evaluation</a></li>
        <li><a href="#technologies">Technologies</a></li>
        <li><a href="#license">License</a></li>
      </ul>
    </td>
        <!-- RIGHT: IMAGE -->
    <td align="center" width="50%">
      <img width="800" alt="Ames house price prediction"
           src="https://github.com/user-attachments/assets/900a3eed-be14-4c13-828a-cb4e07ec86b3" />
    </td>
  </tr>
</table>

---

## Overview

In this project, I develop machine learning models to predict residential property prices in Ames, Iowa. The workflow includes data exploration, feature engineering, and building/optimizing regression models. All analyses and steps are clearly documented.

## Business Motivation

Accurately estimating house prices helps buyers, sellers, and analysts make informed decisions. Using open data, my goal is to deliver robust, interpretable models for this practical need.

## Dataset

The dataset comprises 1460 entries and includes 38 numerical and 43 categorical features, detailing various aspects of each property (e.g., LotArea, YearBuilt, OverallQual).

## Project Workflow

1. **Exploratory Data Analysis (EDA):**
   - Combine train and test datasets for analysis.
   - Identify, visualize, and handle missing values and outliers.
   - Summarize variable distributions.
   - Analyze feature-target relationships.

2. **Feature Engineering:**
   - Treat rare categories and encode variables for modeling.
   - Create new features to improve predictive accuracy.
   - Address missing and extreme values.

3. **Modeling:**
   - Split dataset for training and testing.
   - Build and compare regression models.
   - Tune hyperparameters for optimal results.
   - Evaluate feature importance.

## Usage

Code examples and instructions are provided in the notebooks and scripts within this repository.

---

## Results / Evaluation

The best performing model achieved a root mean squared error (RMSE) of 0.127 on the test data. Key features impacting predictions included OverallQual, GrLivArea, and YearBuilt. Further improvements are possible with additional feature engineering and ensemble methods.

## Technologies

- Python, Pandas, NumPy, scikit-learn
- Visualization: matplotlib, seaborn

## License

This project is MIT licensed.
