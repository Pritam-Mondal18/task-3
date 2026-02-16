# 🏠 House Price Prediction using Linear Regression

## 📌 Project Description
This project implements **Simple and Multiple Linear Regression** using Python and Scikit-learn to predict house prices based on different housing features.  
It covers data preprocessing, model training, evaluation using regression metrics, and interpretation of model coefficients.

This project was completed as part of an **AI & ML Internship Task — Linear Regression**.

---

## 🎯 Objectives
- Import and preprocess the housing dataset  
- Split data into training and testing sets  
- Train Linear Regression model using Scikit-learn  
- Evaluate model using MAE, MSE, and R² score  
- Plot regression line and interpret coefficients  

---

## 🛠 Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## 📂 Dataset
Dataset used: **Housing.csv**

The dataset contains housing-related features such as:
- Area  
- Bedrooms  
- Bathrooms  
- Parking  
- Furnishing status  
- Location-related features  
- Price (Target Variable)

---

## 🔬 Project Workflow

### 1️⃣ Data Preprocessing
- Loaded dataset using Pandas  
- Checked for missing values  
- Converted categorical variables into numerical format using encoding  
- Separated features (X) and target variable (y)

### 2️⃣ Train-Test Split
- Divided dataset into:
  - 80% training data  
  - 20% testing data  

### 3️⃣ Model Training
- Used `LinearRegression` from `sklearn.linear_model`  
- Trained model using training dataset  

### 4️⃣ Model Evaluation
Model performance evaluated using:

- **MAE (Mean Absolute Error)** → Average prediction error  
- **MSE (Mean Squared Error)** → Penalizes larger errors more heavily  
- **R² Score** → Measures how well the model explains variance  

### 5️⃣ Visualization & Interpretation
- Plotted regression line (for selected feature)  
- Interpreted coefficients:
  - Positive coefficient → Price increases with feature  
  - Negative coefficient → Price decreases with feature  
- Intercept represents predicted price when all features are zero  

---

## 📊 Results
The Linear Regression model successfully predicts house prices and shows how different housing features influence price.

---

## 📈 Learning Outcomes
- Data preprocessing techniques  
- Linear regression modeling  
- Model evaluation metrics  
- Coefficient interpretation  
- Data visualization  

---

## 📁 Project Structure
```
Linear-Regression-House-Price/
│
├── Housing.csv
├── task-3.ipynb
└── README.md

```
## ❓ Concepts Covered (Interview Preparation)
- Assumptions of Linear Regression  
- Interpretation of coefficients  
- R² score significance  
- Difference between MAE and MSE  
- Simple vs Multiple Regression  


