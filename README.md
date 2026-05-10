# TurboFan Engine Failure Prediction

## Overview
This project focuses on predicting turbofan engine failures using machine learning. The model analyzes engine sensor data and operational conditions to predict Remaining Useful Life (RUL). The goal is to improve maintenance planning, reduce operational costs, and prevent unexpected engine failures.

---

## Dataset Information

The project uses the CMAPSS (Commercial Modular Aero-Propulsion System Simulation) dataset obtained from Kaggle. The dataset is divided into training, testing, and RUL files for predictive maintenance analysis.

Dataset Link: 
https://drive.google.com/drive/folders/1tgdmEHXZ9QbixiGqX2FnuE1uzR-Pvf-G?usp=sharing

### Train Dataset
The training dataset contains time-series sensor readings and operational settings for multiple turbofan engines from their initial operational cycle until system failure.

### Test Dataset
The test dataset contains sensor and operational data for engines up to a point before failure occurs.

### RUL Dataset
The RUL (Remaining Useful Life) dataset provides the actual remaining operational cycles for each engine in the test dataset.


---

## Workflow

1. Data Collection  
2. Data Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Model Training  
6. Model Evaluation  
7. RUL Prediction  

---

## Models Used

- Ridge Regression (RR)
- Random Forest (RF)
- Gradient Boosting (GB)
- Linear Regression (LR)
- XGBoost

---

## Evaluation Metrics

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score (Coefficient of Determination)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

