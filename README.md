#  Chocolate Sales Profit Prediction  
 End-to-End Machine Learning Project

---

##  Project Overview

This project is a complete end-to-end Machine Learning pipeline built to analyze and predict profitability in a chocolate retail sales dataset.

The dataset consists of multiple relational tables including:
- Sales transactions  
- Customers information  
- Product details  
- Store information  

The goal was to merge, analyze, and model the data to predict whether a sale will generate High or Low Profit.

---

  Problem Statement

Retail businesses need to understand what factors drive profitability.

Can we predict whether a transaction will be profitable based on:
- Product details  
- Customer behavior  
- Store type  
- Discount and quantity  

---

  Project Workflow

  Data Integration
- Merged multiple relational tables using:
  - customer_id  
  - product_id  
  - store_id  

---

  Data Cleaning
- Handled missing values in product information  
- Removed duplicates  
- Ensured consistency across datasets  

---

  Exploratory Data Analysis (EDA)
- Distribution of profit  
- Correlation analysis between numerical features  
- Category-wise and store-wise profit analysis  
- Identified key business insights  

---

  Feature Engineering
- Extracted date-based features (month, day, year)  
- Created customer tenure feature  
- Encoded categorical variables  
- Removed leakage features (revenue, cost)  

---

  Model Building
Two approaches were tested:

 Classification Target:
- Profit converted into:
  - High Profit (1)  
  - Low Profit (0)  

 Models Used:
- Logistic Regression (Baseline)  
- Random Forest Classifier (Final Model)  

---

  Model Evaluation
- Accuracy Score  
- Classification Report  
- Confusion Matrix  

---

 Final Results

- Random Forest performed better than Logistic Regression  
- Captured complex non-linear relationships  
- Provided strong predictive performance for profit classification  

---

  Key Insights

- Discounts have a strong impact on profitability  
- Product category is a major driver of profit variation  
- Store type significantly affects sales performance  
- Quantity sold is a strong predictor of revenue impact  
- Customer behavior influences profit patterns  

---

##  Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

##  Machine Learning Pipeline

Data Collection → Data Merging → Cleaning → EDA → Feature Engineering → Modeling → Evaluation  

---

## 
What I Learned
Data integration from multiple sources
Exploratory Data Analysis (EDA)
Feature engineering techniques
Machine learning model building
Model evaluation and comparison
Business-driven data analysis

Author:
      Mustafa Ahmed
  
