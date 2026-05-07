# 🚗 Car Price Prediction using Linear Regression & Lasso Regression

## 📌 Project Overview
This project predicts the selling price of used cars using Machine Learning techniques.  
The project uses Linear Regression and Lasso Regression models to analyze how factors such as car age, kilometers driven, fuel type, transmission, and brand affect car prices.

The workflow includes data preprocessing, feature engineering, exploratory data analysis (EDA), model training, evaluation, and feature importance analysis.

---

## 🎯 Objective
- Analyze factors affecting used car prices
- Perform data preprocessing and feature engineering
- Build regression models for price prediction
- Compare Linear Regression and Lasso Regression
- Identify important features influencing price

---

## 📂 Dataset
Dataset Used: Used Car Dataset (`car_data.csv`)

Features include:
- Car Name
- Year
- Selling Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner Information

Target Variable:
- Selling Price

---

## 🛠️ Libraries Used
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## ⚙️ Steps Performed

### 1. Import Libraries
Imported required libraries for data analysis, visualization, and machine learning.

### 2. Load Dataset
Loaded dataset using Pandas and inspected basic information.

### 3. Data Cleaning & Feature Engineering
- Extracted car brand from car name
- Removed unnecessary columns
- Converted manufacturing year into car age

### 4. Exploratory Data Analysis (EDA)
Performed visual analysis using:
- Selling price distribution
- Car age vs price
- Kilometers driven vs price
- Correlation analysis

### 5. Encoding Categorical Variables
Applied One-Hot Encoding using `pd.get_dummies()`.

### 6. Train-Test Split
Split dataset into training and testing sets.

### 7. Feature Scaling
Applied StandardScaler to normalize features.

### 8. Model Training
Trained:
- Linear Regression Model
- Lasso Regression Model

### 9. Model Evaluation
Evaluated models using:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

### 10. Residual Analysis
Analyzed residual plots and error distribution to validate model performance.

### 11. Feature Importance
Used Lasso Regression coefficients to identify the most important features affecting price.

### 12. Overfitting Check
Compared train and test scores to analyze model generalization.

---

## 📊 Results
- Linear Regression performed well as a baseline model.
- Lasso Regression helped reduce less important features.
- Car age and kilometers driven negatively affected selling price.
- Brand, fuel type, and transmission significantly influenced car prices.
- Residual analysis indicated reliable model behavior.

---

## 🔍 Key Insights
- Older cars generally have lower selling prices.
- Cars with higher kilometers driven tend to sell for lower prices.
- Premium brands maintain higher resale value.
- Lasso Regression is useful for feature selection and reducing overfitting.

---

## 🚀 Outcome
Successfully built and evaluated Machine Learning models capable of predicting used car prices with good accuracy and meaningful business insights.

---

## 📁 Project Structure

```text
OIBSIP_CarPricePrediction/
│
├── Car_Price_Prediction.ipynb
├── car_data.csv
├── README.md
