# 📊 Employee Turnover Analytics (Machine Learning Project)

## 🧠 Project Overview

This project predicts **employee turnover** using Machine Learning techniques.
The objective is to identify employees likely to leave the company and suggest **retention strategies** based on risk levels.

The dataset contains employee work details such as satisfaction level, evaluation score, number of projects, working hours, promotions, department, and salary.

---

## 🎯 Objectives

* Perform **data quality checks**
* Conduct **Exploratory Data Analysis (EDA)**
* Visualize correlation between features
* Cluster employees who left the company
* Handle class imbalance using **SMOTE**
* Train ML models with **5-fold cross validation**
* Compare models using performance metrics
* Plot ROC curve & confusion matrix
* Predict employee turnover probability
* Categorize employees into risk zones
* Suggest retention strategies

---

## 📁 Dataset

Dataset Source: HR Analytics Dataset
Columns include:

* satisfaction_level
* last_evaluation
* number_project
* average_montly_hours
* time_spend_company
* Work_accident
* left
* promotion_last_5years
* Department
* salary

---

## ⚙️ Technologies Used

* Python 🐍
* Jupyter Notebook 📓
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)

---

## 🔍 Exploratory Data Analysis

* Correlation Heatmap
* Distribution Plots
* Project Count vs Turnover
* Feature Relationship Analysis

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

---

## ⚖️ Handling Class Imbalance

SMOTE (Synthetic Minority Oversampling Technique) was used to balance the dataset before model training.

---

## 📈 Model Evaluation

* 5-Fold Cross Validation
* Confusion Matrix
* ROC Curve
* AUC Score comparison

---

## 🏆 Best Model

Random Forest Classifier performed best based on:

* Higher Recall
* Better ROC-AUC Score
* Balanced performance

---

## 🚦 Risk Zone Categorization

Employees are classified into four categories:

| Zone           | Probability | Meaning             |
| -------------- | ----------- | ------------------- |
| 🟢 Safe Zone   | < 20%       | Low risk            |
| 🟡 Low Risk    | 20% – 60%   | Monitor             |
| 🟠 Medium Risk | 60% – 90%   | Action required     |
| 🔴 High Risk   | > 90%       | Immediate retention |

---

## 💡 Retention Strategies

* 🟢 Safe → Maintain engagement
* 🟡 Low Risk → Training & recognition
* 🟠 Medium Risk → Salary review & promotion
* 🔴 High Risk → HR intervention & role change

---

## ▶️ How to Run

1. Clone the repository
2. Open Jupyter Notebook
3. Install dependencies:

```
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

4. Run all cells step by step

---

## 📊 Output

* Employee turnover prediction
* Risk zone classification
* Retention insights

---

## 👩‍💻 Author

Mugdha Khobare

Machine Learning Enthusiast 🚀

---
