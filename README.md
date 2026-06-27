# 🏠 House Price Prediction using Machine Learning

An end-to-end Machine Learning project to predict house sale prices using advanced regression techniques. The project covers the complete ML workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, hyperparameter tuning, cross-validation, and weighted ensemble learning.

---

## 📌 Project Overview

The objective of this project is to predict the sale price of residential homes based on various property features. Multiple regression models were trained and evaluated, and a weighted ensemble was developed to improve prediction accuracy.

---

## 📂 Dataset

- **Source:** Kaggle - House Prices: Advanced Regression Techniques
- **Training Samples:** 1,460
- **Test Samples:** 1,459
- **Features:** 79 explanatory variables describing residential homes

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

---

## 📊 Exploratory Data Analysis

Performed comprehensive EDA to understand the dataset:

- Missing value analysis
- Distribution of numerical features
- Correlation analysis
- Outlier detection
- Feature relationship visualization

---

## ⚙️ Data Preprocessing

The preprocessing pipeline included:

- Handling missing values
- Outlier removal
- Label Encoding
- One-Hot Encoding
- Log transformation of target variable (`log1p`)
- Box-Cox transformation for skewed numerical features

---

## 🚀 Feature Engineering

Created meaningful features such as:

- TotalSF
- TotalBathrooms
- HouseAge

These engineered features improved model performance by providing additional predictive information.

---

## 🤖 Models Trained

The following regression models were trained and evaluated:

- Ridge Regression
- Gradient Boosting Regressor
- XGBoost Regressor

---

## 🔍 Hyperparameter Tuning

Optimized model performance using:

- RandomizedSearchCV
- 5-Fold Cross Validation

Evaluation Metric:

- Root Mean Squared Error (RMSE)

---

## 📈 Ensemble Learning

Developed a weighted ensemble by combining predictions from multiple models.

Weights were assigned inversely proportional to each model's validation RMSE, giving greater importance to stronger-performing models.

---

## 📁 Project Structure

```
House-Price-Prediction/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── House_Price_Prediction.ipynb
│
├── submission.csv
├── README.md
├── requirements.txt
└── images/
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/House-Price-Prediction.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

Run all cells to reproduce the results.

---

## 📊 Results

The project successfully:

- Built an end-to-end regression pipeline
- Improved prediction accuracy through feature engineering
- Reduced overfitting using cross-validation
- Enhanced performance with hyperparameter tuning
- Achieved better predictions using weighted ensemble learning

---

## 📚 Machine Learning Concepts Used

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Missing Value Imputation
- Feature Engineering
- Encoding Techniques
- Box-Cox Transformation
- Cross Validation
- Hyperparameter Tuning
- Ensemble Learning
- Regression Models
- Model Evaluation

---

## 🙋 Author

**Mohit Raj**

Machine Learning | Data Science

LinkedIn: *www.linkedin.com/in/mohitraj1108*

GitHub: *https://github.com/mra9165*
