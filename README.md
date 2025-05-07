# 🌦️ Rain Prediction Using Australian Weather Data

This project is the **final project submission for the IBM AI Engineering Professional Certificate**  
(Machine Learning with Python Course on Coursera).

## 📁 Project Overview

- **Dataset**: Historical weather data from multiple locations in Australia  
- **Target Variable**: `RainTomorrow` (Yes/No)  
- **Objective**: Build and evaluate machine learning models to predict whether it will rain the next day

## 🧠 Models Used

- Random Forest Classifier  
- Logistic Regression  
- Scikit-learn Pipeline for preprocessing  
- GridSearchCV for hyperparameter tuning

## 📊 Evaluation Metrics

- Accuracy  
- Precision, Recall, F1-Score  
- Confusion Matrix  
- Feature Importance Plot

## ✅ Key Results

- **Random Forest Accuracy**: 84%  
- **Logistic Regression Accuracy**: 83%  
- **True Positive Rate (Recall) for 'Yes' (Rain Tomorrow)** using Logistic Regression: **51%**

## 🔧 Technologies & Libraries

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

## 📝 How to Run

1. Clone this repository  
2. Open `FinalProject_AUSWeather.ipynb` in Jupyter Notebook or VS Code  
3. Run all cells in order to reproduce results

## 📌 Notes

- Dataset includes both numeric and categorical features  
- A custom preprocessing pipeline handles encoding and scaling  
- Potential improvements include using SMOTE for balancing and exploring advanced models like XGBoost

## 🎓 Certificate Context

This project was completed as part of the **IBM AI Engineering Certificate** (Machine Learning with Python course) offered on **Coursera**.

## 📬 Contact

Feel free to open an issue or reach out via GitHub for feedback or questions.
