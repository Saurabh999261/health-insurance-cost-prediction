# 🏥 Health Insurance Cost Prediction

## 📌 Project Overview
Predicted health insurance medical charges using Machine Learning.
Performed end-to-end Data Analysis on 1,300+ insurance records to
identify key cost drivers and built multiple predictive models
using Python and Scikit-learn.

## 🎯 Objective
To identify factors affecting health insurance costs and build a
regression model that accurately predicts medical charges.

## 📊 Dataset
- Records: 1,300+
- Features: Age, BMI, Smoking Status, Gender,
  Region, Number of Children, Charges

## 🔍 Key EDA Findings
- Smoking status, age, and BMI showed strongest impact on charges
- Smokers pay significantly higher medical charges than non-smokers
- Higher BMI directly correlates with increased insurance costs

## 🛠️ Tools & Technologies
- Python | Pandas | NumPy
- Matplotlib | Seaborn
- Scikit-learn

## ⚙️ Models Trained & Evaluated
| Model | Evaluation Metrics |
|---|---|
| Linear Regression | MAE, RMSE, R² |
| Decision Tree Regressor | MAE, RMSE, R² |
| Random Forest Regressor | MAE, RMSE, R² ✅ Best |
| KNN Regressor | MAE, RMSE, R² |

## 🏆 Best Model
**Random Forest Regressor** achieved highest R² score and lowest
prediction error — capturing complex relationships in data more
effectively than all other models.

## 📈 Project Steps
1. Data loading and exploration
2. Exploratory Data Analysis (EDA)
3. Data preprocessing and cleaning
4. Feature engineering
5. Training 4 ML models
6. Evaluation using MAE, RMSE and R² Score
7. Selection of best performing model
