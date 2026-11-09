# 🧬 AIDS Virus Infection Prediction (AIDS Classification)

This repository contains a comprehensive **Machine Learning and Data Science** project developed using AIDS infection data from **Kaggle**. The project covers data preprocessing, outlier removal, automated pipelines, and multi-classifier model comparisons.

---

## 📂 Project Steps

1. **Loading Libraries:** Essential popular libraries for data manipulation, visualization, modeling, and preprocessing (`pandas`, `numpy`, `scikit-learn`, `xgboost`, `catboost`, `lightgbm`, etc.) are imported.
2. **Exploratory Data Analysis (EDA):** The structural properties of the dataset are inspected, including column types, statistical summaries, missing value analyses, and the distribution of the target variable (`infected`).
3. **Data Preprocessing & Cleaning:**
   * Appropriate columns are converted to categorical data types.
   * Outliers in numerical columns are removed using the Z-Score method.
4. **Scikit-Learn Pipeline Architecture:** Separate transformation pipelines (`StandardScaler`, `OneHotEncoder`) are constructed for numerical and categorical variables to prevent data leakage.
5. **Model Selection and Training:** 13 different machine learning algorithms are trained using 5-Fold Cross-Validation and evaluated based on accuracy metrics.

---

## 🤖 Compared Models and Performance

Algorithms tested in the project and their mean accuracy scores (`Accuracy Mean`):

* 🏆 **CatBoost:** ~0.8966
* 🌲 **Random Forest:** ~0.8873
* ⚡ **LGBM:** ~0.8877
* 🟢 **RBF SVM:** ~0.8817
* 🚀 **XGBoost:** ~0.8845
* 🧠 **Neural Net (MLP):** ~0.8835
* *(Other models: AdaBoost, Linear SVM, Decision Tree, K-Nearest Neighbors, Gaussian Process, Naive Bayes, QDA)*

---

## 🛠️ Technologies Used

* **Python**
* **Pandas & NumPy** (Data Analysis)
* **Matplotlib & Seaborn** (Data Visualization)
* **Scikit-Learn** (Preprocessing, Pipelines, and Models)
* **XGBoost, LightGBM, CatBoost** (Advanced Gradient Boosting Models)
