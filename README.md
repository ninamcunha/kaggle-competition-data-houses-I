# 🏡 House Prices - Advanced Regression Techniques (Kaggle Competition)

This repository contains my solution to the Kaggle competition: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

The objective of this challenge is to predict final prices of homes based on various features using advanced regression techniques.

---

## 📘 Notebook Overview

The notebook (`houses_kaggle_competition.ipynb`) follows a complete machine learning workflow, including data preprocessing, model training, feature engineering, and prediction generation.

### 1. 📦 Data Loading & Exploration
- Loaded `train.csv` and `test.csv` from Kaggle.
- Explored dataset dimensions, feature types, and missing values.
- Referred to external dataset documentation for feature definitions.

### 2. 🐣 Baseline Model
- Built an initial pipeline using `scikit-learn`.
- Included simple preprocessing and a default regressor.
- Performed cross-validation to evaluate the baseline.
- Generated baseline predictions for the test set.

### 3. 🏋️‍♀️ Model & Preprocessing Iterations

#### Preprocessing Enhancements
- Applied `OrdinalEncoding` for categorical variables.
- Conducted **feature selection**:
  - Option 1: Univariate statistical tests
  - Option 2: Multivariate correlation-based methods
  - Option 3: Unsupervised feature selection
- Transformed cyclical features (e.g., month, year).
- Engineered and transformed the target variable to improve regression accuracy.

#### Model Training
Evaluated a variety of models including:

- **Linear Models**: Lasso, Ridge, ElasticNet, SGDRegressor
- **Distance-Based**: K-Nearest Neighbors
- **Kernel-Based**: Support Vector Machines
- **Tree-Based**:
  - Decision Trees
  - Random Forest
  - Gradient Boosting
- **Ensembles**:
  - AdaBoost
  - Voting Regressor
  - Stacking Regressor
- **Advanced**: XGBoost (final model of choice)

### 4. 🏁 Final Submission
- Selected the best-performing model after evaluation.
- Used the full training dataset to retrain.
- Generated predictions on the test set in the required Kaggle format.

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn
- XGBoost

---

## 📁 Repository Contents

- `houses_kaggle_competition.ipynb`: Main notebook with the full pipeline and model development.
- `README.md`: Project documentation (this file).

---

## 🥇 Goal

Achieve high accuracy on house price predictions and rank competitively on the Kaggle leaderboard through iterative experimentation and model tuning.

