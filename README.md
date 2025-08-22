# 🏥 Medical Cost Insurance Prediction

Predicting individual **medical insurance costs** based on health, lifestyle, and demographic factors using **Machine Learning**.  
This project compares three regression models — **Linear Regression**, **Random Forest Regressor**, and **XGBoost Regressor** — to identify the most accurate approach.

---

## 📌 Project Overview
Medical insurance companies and individuals often need an accurate estimate of medical costs.  
In this project, we:
- Built a **machine learning pipeline**.
- Performed **data cleaning**, **feature engineering**, and **visualizations**.
- Implemented and compared three ML models.
- Evaluated models using **R² Score** and **MAE**.

---

## 📂 Dataset
The dataset contains the following features:
- **age** → Age of the individual
- **sex** → Gender
- **bmi** → Body Mass Index
- **children** → Number of dependents
- **smoker** → Smoking status (yes/no)
- **region** → Residential region
- **charges** → Medical insurance cost *(Target)*

---

## 🛠️ Tech Stack
- **Programming Language:** Python 🐍
- **Libraries & Tools:**
  - **Pandas**, **NumPy** → Data processing
  - **Matplotlib**, **Seaborn** → Visualization
  - **Scikit-learn** → ML modeling

---

## 🚀 Models Implemented
| Model                     | R² Score | RMSE |
|--------------------------|----------|------|
| **Linear Regression**    | 0.74     | 4272 | 
| **Random Forest**        | 0.930    | 1597 | 
| **XGBoost**              | 0.933    | 1464 | 

---

## 📊 Exploratory Data Analysis (EDA)
- Distribution of insurance charges
- Impact of **smoking** and **BMI** on costs
- Regional medical cost variations
- Correlation heatmaps for feature relationships


git clone https://github.com/your-username/medical-cost-insurance-prediction.git
cd medical-cost-insurance-prediction
