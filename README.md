# Customer Churn Prediction using Machine Learning

## 📌 Project Overview

This project focuses on analyzing customer behavior and predicting churn using machine learning techniques. The goal is to identify customers who are likely to discontinue services and provide actionable insights to improve retention strategies.

---

## 🧩 Problem Statement

Customer churn directly impacts business revenue and growth. By leveraging historical customer data, this project aims to:

* Understand key factors influencing churn
* Build predictive models to classify churned vs non-churned customers
* Support data-driven decision-making for retention

---

## 📊 Dataset Description

The dataset contains customer demographic, account, and service usage information including:

* Numeric features (age, tenure, balance, products count, etc.)
* Categorical features (gender, geography, contract type, services, etc.)
* Target variable: **Churn** (1 = Yes, 0 = No)

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing

* Handling missing values
* Encoding categorical variables (One-Hot Encoding)
* Feature scaling for numerical attributes
* Train-test split with stratification

### 2️⃣ Exploratory Data Analysis (EDA)

* Univariate and bivariate analysis
* Distribution analysis of churned vs retained customers
* Correlation heatmap for numeric features
* Insights on key churn-driving variables

### 3️⃣ Feature Engineering

* Selection of relevant features
* Transformation using ColumnTransformer
* Pipeline-based preprocessing for consistency

### 4️⃣ Model Building

Multiple classification models were trained and evaluated:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier
* AdaBoost Classifier
* Support Vector Classifier (SVC)

---

## 🧪 Model Evaluation

* Stratified K-Fold Cross Validation
* Evaluation Metric: **ROC-AUC Score**
* Comparison of models based on mean and standard deviation of ROC-AUC

### Performance Metrics on Test Set

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix Visualization

---

## ⭐ Best Model Selection

The best-performing model was selected based on cross-validation ROC-AUC score and further evaluated on the test dataset using a full performance report.

---

## 🔍 Feature Importance Analysis

For tree-based models (Random Forest / Gradient Boosting):

* Extracted feature importance values
* Visualized top 20 most influential features
* Identified key drivers contributing to customer churn

---

## 📈 Key Insights & Conclusions

* Certain customer demographics and service usage patterns strongly influence churn
* Imbalanced behavior observed between churned and retained customers
* Ensemble models outperformed linear models in capturing complex patterns

---

## 🚀 Future Improvements & Enhancements

* Hyperparameter tuning using GridSearchCV / RandomizedSearchCV
* Handling class imbalance using SMOTE or class weights
* Deploying the model using Flask / FastAPI
* Real-time churn prediction dashboard (Power BI / Streamlit)
* Incorporating customer interaction and behavioral data

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **ML Techniques:** Classification, Cross Validation, Pipelines
* **Visualization:** Heatmaps, Bar plots, Confusion Matrix

---

## 📂 Project Structure

```
├── data/
├── notebooks/
│   └── EDA_and_Modeling.ipynb
├── README.md
└── requirements.txt
```

---

## 👤 Author

**Hitesh Moota**
Final Year BE (AI & DS)

---

## 📄 License

This project is for academic and learning purposes.
