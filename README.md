COMPANY : CODTECH IT SOLUTIONS

NAME : PRAJAKTA SIDANKAR

DOMAIN : DATA ANALYSIS

DURATION : 4 WEEKS

🧠 Task 2: Predictive Analysis using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![scikit-learn](https://img.shields.io/badge/ML-scikit--learn-yellow?logo=scikit-learn)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

📌 Project Overview

This project is part of my data analysis internship. The objective was to perform *predictive analysis using machine learning* by building a regression model that can predict housing prices. 

Using the *Boston Housing dataset*, the project demonstrates the full machine learning pipeline — including *data exploration, feature selection, model training*, and *evaluation* — all performed in a *Jupyter Notebook* using Python.

🎯 Objective

- Build a regression model to predict *house prices* (target: `medv`)
- Apply preprocessing and feature selection techniques
- Train and evaluate the model using *scikit-learn*
- Visualize and interpret predictions

🛠️ Technologies Used

- Python 3.10  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn

📂 Dataset

Dataset: [Boston Housing Dataset (CSV)](https://raw.githubusercontent.com/selva86/datasets/master/BostonHousing.csv)  
File Used: `BostonHousing.csv`  
Target Column: `medv` (Median house price)

🔍 Workflow

 1. Import Libraries  
Standard libraries for data manipulation, visualization, and modeling

 2. Load Dataset  
Loaded `BostonHousing.csv` into a pandas DataFrame

 3. Data Exploration  
- Summary statistics
- Correlation heatmap
- Feature inspection

 4. Feature Selection & Preprocessing  
- Dropped target column (`medv`) from feature set
- Verified data for nulls
- Applied one-hot encoding (if necessary)

5. Model Training  
Used *Linear Regression* to model the data:
```python
from sklearn.linear_model import LinearRegression
