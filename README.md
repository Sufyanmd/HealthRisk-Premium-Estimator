# HealthSure – Medical Insurance Claim Predictor (In Progress)

HealthSure is a machine learning project that aims to predict **medical insurance claim amounts** based on key health and lifestyle factors such as age, BMI, smoking status, and region.  
The goal is to build a complete end-to-end ML pipeline — from data analysis to deployment as an interactive web application.

This project is currently under development and will be updated as each stage is completed.

---

## Current Project Status: Building Phase

### Data Exploration & Understanding (Completed)
- Loaded insurance dataset using **Pandas**
- Checked for missing values and duplicates
- Analyzed data distribution (histograms, bar plots, box plots)
- Generated a **correlation heatmap** to identify key relationships
- Created categorical features such as:
  - Age groups
  - BMI categories
  - Smoker/Non-smoker encoding

### Model Development (In Progress)
- Preparing data for training using:
  - Label Encoding
  - Feature Scaling
  - Train-test split
- Training multiple Regressors:
  - Linear Regression
  - Random Forest Regressor
  - Support Vector Regressor (SVR)
  - XGBoost Regressor
- Evaluating models using:
  - **R² Score**
  - **Mean Absolute Error (MAE)**
  - **Root Mean Squared Error (RMSE)**

    
---

## Project Objective

The purpose of HealthSure is to:

1. Understand how various health factors influence medical expenses  
2. Build a predictive model that estimates insurance claim amounts  
3. Deploy the model as a simple and user-friendly web app  

This aligns with real-world applications where insurance companies use ML to estimate risk and pricing.

---

## Tech Stack

### **Data Analysis & Visualization**
- Python  
- Pandas  
- Matplotlib  
- Seaborn  

### **Machine Learning & Modeling**
- Scikit-learn  
- XGBoost  
- NumPy  
- Joblib  

### **Deployment**
- Streamlit (upcoming)
- Pickle/Joblib model integration

---

## Goals for Final Version

- Accurate ML model with tuned parameters  
- Clean, understandable visualizations  
- Fully interactive Streamlit web app  
- Real-time prediction based on user input  
- Clear explanation of insights and feature impact  

---

## Note
This repository will be updated continuously as development progresses.  
Feel free to ⭐ star the repo if you want to follow along!



