# telecom-churn-prediction-ml
Telecom churn prediction using machine learning with Random Forest.Includes data preprocessing, feature encoding, model training, evaluation, and business insights. Power BI dashboard used for EDA and visualization.

# 📊 Telecom Customer Churn Prediction

## Problem Statement

Customer churn is a critical issue in the telecom industry, directly impacting revenue and growth. Retaining existing customers is far more cost-effective than acquiring new ones.
This project aims to **predict customer churn using machine learning**, enabling telecom companies to identify high-risk customers early and take proactive retention measures.

##  Dataset Overview

The dataset consists of customer information from a telecom service provider, including:

### Feature Categories

* **Demographics**: Gender, Age, marital status
* **Service Details**: Internet service, streaming services, premium support etc
* **Account Information**: Contract type, payment method, tenure, monthly charges
* **Target Variable**: `Churn` (Yes / No)

### 🔹 Dataset Characteristics

* Combination of **categorical and numerical features**
* No sensitive or personally identifiable information
* Requires preprocessing and encoding before model training

## Machine Learning Approach

The workflow followed in this project:

1. **Data Cleaning**

   * Handled missing values
   * Converted target variable into numerical format

2. **Exploratory Data Analysis (EDA)**

   * Analyzed churn trends based on tenure, contract type, and charges
   * Identified key patterns influencing churn

3. **Feature Engineering**

   * Encoded categorical variables
   * Prepared features for model compatibility

4. **Model Training**

   * Split data into training and testing sets
   * Trained and evaluated classification models


## 🌲 Model Used: Random Forest

The **Random Forest Classifier** was selected due to:

* Strong performance on **tabular data**
* Ability to handle **non-linear relationships**
* Reduced overfitting through ensemble learning
* Built-in **feature importance analysis**


### 🔹 Key Insights

* The model demonstrated **robust predictive performance**
* Successfully identified customers with a high likelihood of churn
* Important churn-driving factors included:

  * Contract type
  * Tenure
  * Monthly charges
  * Value-added services

## 🚀 Business Impact

This churn prediction system can help telecom companies:

* Identify at-risk customers early
* Design targeted retention campaigns
* Reduce churn rate and improve customer lifetime value

## 🛠️ Tech Stack

* **Python**
* **Pandas, NumPy**
* **Scikit-learn**
* **Jupyter Notebook**
* **Power BI** (for data visualization & insights)
