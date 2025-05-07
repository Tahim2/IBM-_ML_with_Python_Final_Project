# 🌦️ Rain Prediction Using Australian Weather Data

This project uses machine learning models to predict whether it will rain tomorrow in Australia based on weather observations such as temperature, humidity, wind speed, pressure, and more.

## 📁 Project Overview

- **Dataset**: Historical weather data from various Australian locations  
- **Target Variable**: `RainTomorrow` (Yes/No)  
- **Goal**: Build a classification model to predict if it will rain the next day  

## 🧠 Models Used

- Random Forest Classifier  
- Logistic Regression  
- Pipeline with preprocessing (numeric + categorical)  
- GridSearchCV for hyperparameter tuning  

## 📊 Evaluation Metrics

- Accuracy  
- Precision, Recall, F1-Score  
- Confusion Matrix  
- Feature Importance

## ✅ Key Results

- **Random Forest Accuracy**: 84%  
- **Logistic Regression Accuracy**: 83%  
- Logistic Regression Recall for “Yes” (True Positive Rate): **51%**

## 🔧 Technologies

- Python, Pandas, NumPy  
- Scikit-learn (Pipeline, GridSearchCV, Classifiers)  
- Matplotlib, Seaborn  

## 📌 How to Run

1. Clone this repository  
2. Open `FinalProject_AUSWeather.ipynb` in Jupyter or VS Code  
3. Run the notebook cells sequentially  

## 📎 Note

This model can be improved with further feature engineering, SMOTE for class imbalance, and advanced models (e.g., XGBoost).

## 📬 Contact

For questions or feedback, feel free to open an issue or message me directly.

