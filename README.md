# 🚖 Taxi Trip Fare Prediction - Databricks ML Project

## 📌 Overview
This Databricks project focuses on building and evaluating various machine learning regression models to predict taxi trip fares based on trip-related features. The goal is to compare model performance and select the best one using RMSE (Root Mean Square Error) as the metric.

## 🧪 Models Used
The following regression models were trained and evaluated:
- 🐈‍⬛ CatBoost Regressor
- 🌲 Random Forest Regressor
- 🌟 Gradient Boosting Regressor
- 🚀 XGBoost Regressor
- 🧷 Lasso Regression

## 📈 Model Performance Summary (Lower RMSE = Better)
| Model              | RMSE         |
|--------------------|--------------|
| **CatBoost**       | **875.60**   |
| XGBoost            | 897.57       |
| RandomForest       | 1189.80      |
| GradientBoosting   | 1500.45      |
| Lasso              | 3137.77      |

## 🧰 Tech Stack
- 🧠 **Machine Learning:** Scikit-learn, XGBoost, CatBoost
- 💻 **Platform:** Databricks Notebook (.dbc)
- 🐍 **Language:** Python (PySpark optionally if used elsewhere)

## 📁 File
- `taxi_trip (1).dbc`: Archive of all Databricks notebooks used for training, evaluation, and visualization.

## 🧑‍🏫 How to Run
1. Import the `.dbc` file into your Databricks workspace.
2. Open the notebook inside the workspace.
3. Attach it to a cluster (with appropriate libraries installed).
4. Run all cells sequentially.

## 🔧 Dependencies
- `scikit-learn`
- `xgboost`
- `catboost`
- Databricks Runtime with ML support (or manually install missing packages)

## 👨‍💻 Author
**Vasu Arora**  
