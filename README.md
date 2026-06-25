# credit-limit-prediction-analysis

## 📌 Project Overview

This project demonstrates an end-to-end data analytics and machine learning workflow for predicting customer credit limits using demographic and financial information.

The objective is to identify the factors that influence credit allocation and build a predictive model that can estimate customer credit limits with high accuracy.

---

## 🎯 Business Problem

Financial institutions must balance customer growth with financial risk. Understanding which customer characteristics are associated with higher credit limits helps banks:

* Improve credit decision-making
* Reduce lending risk
* Enhance customer segmentation
* Support data-driven financial strategies

---

## 📊 Dataset

The dataset contains over **10,000 customer records** with demographic, financial, and transaction-related information.

Example features include:

* Customer Age
* Gender
* Education Level
* Income Category
* Marital Status
* Credit Card Category
* Total Transaction Amount
* Total Transaction Count
* Average Utilization Ratio
* Credit Limit (Target Variable)

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 🔍 Project Workflow

### 1. Data Cleaning

* Handled missing values
* Removed unnecessary columns
* Checked data types
* Performed initial data inspection

### 2. Feature Engineering

* Binary encoding for Gender
* Ordinal encoding for Education Level
* Ordinal encoding for Income Category
* Created Age Groups
* Selected relevant predictive features

### 3. Exploratory Data Analysis (EDA)

Visualizations include:

* Credit Limit vs Income Category
* Customer Age Distribution
* Credit Limit by Age Group
* Marital Status by Income
* Correlation Heatmaps
* Feature Importance

### 4. Machine Learning

Model used:

* Random Forest Regressor

Model evaluation metrics:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 5. Hyperparameter Tuning

Optimized the model using:

* GridSearchCV
* RandomizedSearchCV

---

## 📈 Results

Initial Random Forest model achieved:

* **R² Score:** **0.86**
* **MAE:** **1313.70**
* **RMSE:** **3471.81**

The most important features influencing credit limit prediction were:

* Income Category
* Average Utilization Ratio
* Total Revolving Balance
* Total Transaction Amount

---
---

## 🚀 Future Improvements

* Compare multiple regression algorithms (XGBoost, LightGBM, CatBoost)
* Build an interactive dashboard using Power BI or Tableau
* Deploy the model using Streamlit or Flask
* Perform advanced feature engineering
* Implement cross-validation and model monitoring

---

## 📚 Key Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Visualization
* Machine Learning
* Model Evaluation
* Hyperparameter Tuning
* Predictive Analytics
* Python Programming

---

## 👤 Author

**Mayank Goel**

Aspiring Data Analyst | Python | SQL | Power BI | Excel | Machine Learning

Feel free to connect or provide feedback on this project.
