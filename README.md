<h1 align="center">Titanic Survival Prediction – Classification Analysis</h1>

<table align="center">
  <tr>
    <!-- LEFT: TABLE OF CONTENTS -->
    <td align="left" width="30%" style="vertical-align: top;">
      <h3>📑 Table of Contents</h3>
      <ul>
        <li><a href="#overview">Overview</a></li>
        <li><a href="#dataset">Dataset</a></li>
        <li><a href="#methodology">Methodology</a></li>
        <li><a href="#results">Results</a></li>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#author">Author</a></li>
      </ul>
    </td>
    <!-- RIGHT: IMAGE -->
    <td align="center" width="70%">
      <img width="800" alt="Titanic project cover"
           src="https://github.com/user-attachments/assets/7d449a16-e70d-421d-9cef-640240a68d71" />
    </td>
  </tr>
</table>

---

## 📌 Project Overview
This project covers the full machine learning workflow used for the competition:  
exploratory analysis, data preprocessing, feature engineering, model development, and generating a submission file for Kaggle.

Main files in this repository:
- **`Titanic_Competition.ipynb`** — Notebook containing the entire workflow.  
- **`titanic.csv`** — Submission file produced from the final model.

---

## 📂 Dataset
The competition dataset consists of two files provided by Kaggle:

- **`train.csv`** — Passenger data with survival labels.  
- **`test.csv`** — Same structure as the training data but without labels.

---

## 🔧 Methodology

### 1. Setup
Installed and imported the required libraries:  
`pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`, and `lightgbm`.

### 2. Data Loading
Loaded the training dataset and performed an initial inspection.

### 3. Preprocessing
- Handled missing values (Age, Cabin, Embarked).  
- Created new features like **FamilySize**, **Title**, and **AgeGroup**.  
- Encoded categorical variables and standardized selected numerical fields.

### 4. Exploratory Data Analysis
Visualized survival patterns by gender, passenger class, age, and other variables.

### 5. Feature Engineering
Used label encoding, one-hot encoding, and extracted structured information from names.

### 6. Model Selection
Tested multiple baseline models:
- K-Nearest Neighbors (KNN)  
- Random Forest Classifier  

Random Forest showed the strongest baseline performance.

### 7. Training & Validation
Evaluated models through cross-validation to ensure generalization.

### 8. Hyperparameter Tuning
Optimized the Random Forest using `GridSearchCV`.

### 9. Model Evaluation
Metrics used:
- Accuracy  
- F1 Score  
- ROC AUC  

### 10. Final Predictions
Generated predictions for the test set and saved them to **`titanic.csv`** in the required format.

---

## 📈 Results
- **Best Model:** Random Forest Classifier  
- **Cross-validated Accuracy:** **83.21%**

---

## 🛠 Dependencies
- Python 3.x  
- Jupyter Notebook  
- pandas  
- numpy  
- seaborn  
- matplotlib  
- scikit-learn  
- lightgbm  

---

## 👤 Author
**Eray Yuztyurk**
