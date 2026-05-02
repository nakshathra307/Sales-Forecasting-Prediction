# 🛒 Big Mart Sales Forecasting
### Machine Learning Regression Model

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-LightGBM-green)
![Dataset](https://img.shields.io/badge/Dataset-Big%20Mart%20Sales-orange)

## 📌 Overview
A machine learning model to predict item-level outlet sales for Big Mart stores using structured retail data. The project covers the full data science pipeline — from exploratory data analysis and feature engineering to model comparison and hyperparameter tuning.

## 📊 Dataset
- **Source:** Big Mart Sales Dataset (`Train.csv`)
- **Size:** 8,523 rows × 12 columns
- **Features:** Item attributes (weight, MRP, fat content, type, visibility) and outlet attributes (size, type, location, age)
- **Target:** `Item_Outlet_Sales` — sales of each product at a particular outlet

## ⚙️ Methodology
- ✅ Exploratory Data Analysis and correlation heatmap
- ✅ Missing value imputation for `Item_Weight` and `Outlet_Size`
- ✅ Feature engineering — `New_Item_Type`, `Outlet_Years`, fat content standardisation
- ✅ Label encoding and one-hot encoding for categorical variables
- ✅ Log transformation on target variable to handle skewness
- ✅ Compared Linear Regression, Ridge, Lasso, Decision Tree, Random Forest, Extra Trees, XGBoost
- ✅ Hyperparameter tuning with `RandomizedSearchCV` on Random Forest, LightGBM, and XGBoost
- ✅ Evaluated using R² Score and Mean Squared Error (5-fold cross-validation)

## 🏆 Best Model Results

| Model | Test R² |
|---|---|
| Linear Regression | 0.7136 |
| Ridge Regression | 0.7132 |
| Random Forest (tuned) | 0.7108 |
| XGBoost (tuned) | 0.7392 |
| **LightGBM (tuned)** | **0.7421** ✅ |

## 🛠️ Tools & Technologies
`Python` `Scikit-learn` `XGBoost` `LightGBM` `Pandas` `NumPy` `Matplotlib` `Seaborn`

## 👩‍💻 Author
**[Nakshathra Pramoj]** — [Bioinformatics Student | Aspiring Data Analyst | Machine Learning Enthusiast]  
[LinkedIn](www.linkedin.com/in/nakshathra-pramoj-640730250) | [GitHub](https://github.com/nakshu307)
