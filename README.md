# 🏥 Health Insurance Cost Prediction using Machine Learning

## 📌 Project Overview
An end-to-end Machine Learning project to predict health insurance costs based on customer attributes such as Age, BMI, Smoking Status, Gender, Region, and Number of Children. The project combines Exploratory Data Analysis (EDA), data preprocessing, feature engineering, and multiple regression models to identify key cost drivers and accurately estimate insurance charges.

---

## 🎯 Project Objectives
- Predict health insurance charges using customer demographic and health-related data.
- Compare multiple Machine Learning regression models to identify the best-performing algorithm.
- Discover the most influential factors affecting insurance costs.
- Demonstrate an end-to-end Machine Learning workflow, from data preprocessing to model evaluation.

---

## 💼 Business Problem
Health insurance providers need to estimate future medical costs accurately to design effective pricing strategies and manage financial risk. This project develops predictive models that estimate insurance charges using customer demographic and health-related information, enabling more informed business decisions.

---

## 📊 Dataset Details

- **Records:** 1,300+
- **Target Variable:** Health Insurance Charges

| Feature | Description |
|---------|-------------|
| Age | Customer age |
| Gender | Male / Female |
| BMI | Body Mass Index |
| Children | Number of dependent children |
| Smoking Status | Smoker / Non-Smoker |
| Region | Customer location |

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## 📈 Project Workflow

### 1️⃣ Data Preprocessing

- Loaded the dataset
- Checked dataset shape, data types, and summary information
- Identified and handled missing values using mean imputation
- Removed duplicate records
- Encoded categorical variables using Label Encoding:
  - Gender
  - Smoking Status
  - Region

---

### 2️⃣ Exploratory Data Analysis (EDA)

Performed **8+ visualizations** to understand the dataset.

- Distribution of Insurance Charges (Histogram + KDE)
- Smoking Status vs Insurance Charges (Box Plot)
- Age vs Insurance Charges (Scatter Plot)
- BMI vs Insurance Charges (Scatter Plot)
- Gender vs Insurance Charges (Box Plot)
- Region vs Insurance Charges (Box Plot)
- Children vs Insurance Charges (Box Plot)
- Correlation Heatmap
- Pair Plot for feature relationships

---

### 3️⃣ Feature Engineering

- Converted categorical variables into numerical values using Label Encoding.
- Separated Features (**X**) and Target Variable (**y**).
- Performed an **80:20 Train-Test Split** (`random_state = 42`).

---

### 4️⃣ Machine Learning Models

| Model | Type |
|--------|------|
| Linear Regression | Baseline Model |
| Decision Tree Regressor | Tree-based Model |
| Random Forest Regressor | Ensemble Model |
| K-Nearest Neighbors (KNN) Regressor | Distance-based Model |

---

### 5️⃣ Model Evaluation

The models were evaluated using the following performance metrics:

| Metric | Purpose |
|---------|----------|
| MAE | Mean Absolute Error |
| MSE | Mean Squared Error |
| RMSE | Root Mean Squared Error |
| R² Score | Coefficient of Determination |

---

## 🏆 Best Performing Model

**Random Forest Regressor** achieved the best overall performance, with the highest **R² Score (0.875)** and the lowest prediction error among all four models.

```text
Random Forest Regressor

R² Score : 0.875
MAE      : 2749.36
RMSE     : 4793.46
```

---

## 📊 Model Comparison

| Model | R² Score | MAE | RMSE |
|--------|---------:|----:|------:|
| Linear Regression | 0.800 | 4259.77 | 6056.83 |
| Decision Tree | 0.765 | 3249.59 | 6575.92 |
| **Random Forest** | **0.875** | **2749.36** | **4793.46** |
| KNN | 0.062 | 8906.65 | 13130.07 |

---

## 🔍 Key Insights

- Smoking Status is the strongest predictor of insurance charges.
- Higher BMI is associated with increased insurance costs.
- Age shows a strong positive relationship with insurance charges.
- Gender and Region have relatively lower influence on insurance costs.
- Random Forest outperformed all other regression models.
- KNN produced lower performance because distance-based algorithms are highly sensitive to feature scaling.
- Feature Importance analysis confirmed **Smoking Status, Age, and BMI** as the three most influential variables.

---

## 💼 Business Value

- Helps insurance companies estimate future medical costs more accurately.
- Supports pricing strategy and risk assessment.
- Demonstrates how Machine Learning can improve predictive analytics for the insurance industry.

---

## 💡 Skills Demonstrated

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Label Encoding
- Machine Learning (Regression)
- Model Evaluation & Comparison
- Predictive Analytics

---

## 📁 Project Structure

```text
Health-Insurance-Cost-Prediction
│
├── Health_Insurance_Cost_Prediction.ipynb
├── README.md
└── Dataset
```

---

## 🚀 Future Improvements

- Apply Feature Scaling to improve KNN model performance.
- Experiment with advanced ensemble models such as XGBoost and Gradient Boosting.
- Use a larger dataset to improve model generalization.
- Build a Streamlit web application for real-time insurance cost prediction.

---

## 👤 Author

**Saurabh Mekhe**

**Data Analyst | Python | SQL | Power BI | Machine Learning**

- **LinkedIn:** https://www.linkedin.com/in/saurabh-mekhe-7b5aa6324
- **GitHub:** https://github.com/Saurabh999261
