# 🚢 Titanic Survival Prediction - EDA & Machine Learning

## 📊 Project Overview
This project performs Exploratory Data Analysis (EDA) and builds a predictive model to determine which passengers survived the Titanic disaster.

Dataset used: Titanic dataset (Kaggle)

---

## 🔍 Steps Performed

### 1️⃣ Data Cleaning
- Removed irrelevant columns (PassengerId, Name, Ticket)
- Filled missing Age values using median
- Filled missing Embarked values using mode
- Dropped Cabin due to excessive missing data

### 2️⃣ Exploratory Data Analysis (EDA)
- Visualized Age and Fare distributions
- Analyzed survival patterns by Gender and Passenger Class
- Correlation heatmap analysis
- Identified key survival factors

### 3️⃣ Feature Engineering
- Created FamilySize feature
- Encoded categorical variables
- Removed multicollinearity features

---

## 🤖 Machine Learning Models Used

### Logistic Regression
Accuracy: 80.44%

### Random Forest
Accuracy: 81.56%

Cross-validation score: 78.9%

---

## 📈 Key Findings

- Gender (Sex) is one of the strongest predictors of survival.
- Fare and Passenger Class significantly influence survival.
- Random Forest slightly outperformed Logistic Regression.
- Survival prediction is feasible with basic feature engineering.

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📌 Conclusion
This project demonstrates end-to-end data science workflow including data cleaning, EDA, feature engineering, model building, and evaluation.
