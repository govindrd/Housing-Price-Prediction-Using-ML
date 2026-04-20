# 🏠 Housing Price Prediction (Machine Learning)

<p align="center">
  <img src="IFYOUF~1.JPG" width="800">
</p>

---

## 📌 Project Overview

This project develops a complete end-to-end machine learning pipeline to predict residential property prices using regression and ensemble boosting algorithms.

The solution follows an industry-standard workflow including:

- Data cleaning and preprocessing  
- Feature engineering  
- Cross-validation model comparison  
- Hyperparameter tuning  
- Model performance evaluation and error analysis  

The objective is to build a robust predictive model capable of generalizing well to unseen housing data.

---

## 📊 Dataset

**House Prices – Advanced Regression Techniques**  
Source: Kaggle  

This dataset contains 79 explanatory variables describing residential homes, including structural, location-based, and economic attributes.

---

## 🔎 Exploratory Data Analysis

### Correlation Heatmap

<p align="center">
  <img src="Screenshot 2026-02-13 182942.png" width="700">
</p>

### Key Insights

- Median income shows strong positive correlation with house value.
- Total rooms, bedrooms, and households are highly correlated.
- Location variables (latitude & longitude) influence pricing patterns.
- Non-linear relationships justify use of boosting models.

---

## ⚙️ Machine Learning Pipeline

### 1️⃣ Data Preprocessing

- Missing value imputation (median for numerical, most frequent for categorical)
- One-hot encoding of categorical variables
- Feature scaling for numerical variables
- Implemented using `ColumnTransformer` and `Pipeline`

---

### 2️⃣ Feature Engineering

- Derived additional ratio-based features
- Removed redundant columns
- Improved predictive performance through structured transformations

---

### 3️⃣ Model Comparison (Cross-Validation)

Models evaluated using K-Fold Cross Validation:

- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Random Forest Regressor  
- HistGradientBoosting Regressor  

Evaluation Metrics:

- Root Mean Squared Error (RMSE)  
- Mean Absolute Error (MAE)  
- R² Score  

---

### 4️⃣ Hyperparameter Tuning

- Applied `GridSearchCV` to optimize boosting model performance
- Selected best parameters based on cross-validation results

---

### 5️⃣ Model Evaluation

- Compared cross-validation scores
- Analyzed residual distribution
- Evaluated predicted vs actual house prices

---

## 📈 Results & Observations

- Boosting models outperformed linear regression models.
- Cross-validation improved reliability of performance estimates.
- Feature engineering significantly enhanced prediction accuracy.

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 👩‍💻 Author

**Anamika Singh Raj**  
Aspiring Data Analyst | Machine Learning Enthusiast




