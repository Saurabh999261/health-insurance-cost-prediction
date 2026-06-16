# 🏥 Health Insurance Cost Prediction using Machine Learning

## 📌 Project Overview
An end-to-end Machine Learning project to predict health insurance
costs based on customer attributes such as age, BMI, smoking status,
gender, location, and number of children. The project combines
Exploratory Data Analysis (EDA), data preprocessing, and multiple
regression models to identify key cost drivers and estimate insurance
charges accurately.

## 💼 Business Problem
Health insurance providers need to estimate future medical costs
accurately in order to design pricing strategies and manage risk
effectively. This project builds predictive models that estimate
insurance charges using customer demographic and health-related
information.

## 📊 Dataset Details
- Records: 1,300+
- Target Variable: Health Insurance Price

| Feature | Description |
|---|---|
| Age | Customer age |
| Gender | Male / Female |
| BMI | Body Mass Index |
| Children | Number of dependent children |
| Smoking Status | Smoker / Non-smoker |
| Location | Customer location |

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## 📈 Project Workflow

### 1. Data Preprocessing
- Loaded dataset from Excel file
- Checked shape, info, and data types
- Identified and handled null values using mean imputation
- Removed duplicate records
- Encoded categorical variables using Label Encoding
  — Gender, Smoking Status, Location

### 2. Exploratory Data Analysis — 8 Visualizations
- Distribution of Health Insurance Prices — Histogram + KDE
- Smoking Status vs Insurance Price — Box Plot
- Age vs Insurance Price — Scatter Plot
- BMI vs Insurance Price — Scatter Plot
- Gender vs Insurance Price — Box Plot
- Location vs Insurance Price — Box Plot
- Children vs Insurance Price — Box Plot
- Correlation Heatmap — all numeric features
- Pair Plot — complete feature relationships

### 3. Feature Engineering
- Converted categorical variables to numerical using Label Encoding
- Separated features (X) and target variable (y)
- Train Test Split — 80% training, 20% testing (random_state=42)

### 4. Machine Learning Models
| Model | Type |
|---|---|
| Linear Regression | Baseline model |
| Decision Tree Regressor | Tree based model |
| Random Forest Regressor | Ensemble model |
| KNN Regressor | Distance based model |

### 5. Model Evaluation
All 4 models evaluated using:

| Metric | Purpose |
|---|---|
| MAE | Mean Absolute Error |
| MSE | Mean Squared Error |
| RMSE | Root Mean Squared Error |
| R² Score | Model accuracy |

## 🏆 Best Model
**Random Forest Regressor** achieved the highest R² score and
lowest prediction error — capturing complex relationships in
data more effectively than all other models.

## 🔍 Key Insights
- Smoking status is the strongest predictor of insurance cost
- Higher BMI directly correlates with increased insurance charges
- Age shows strong positive correlation with insurance price
- Gender and location have relatively lower impact on charges
- Random Forest outperformed all other regression models
- KNN underperformed (low R² score) due to features not being
  scaled — distance-based models like KNN are sensitive to
  differing feature ranges, unlike tree-based or linear models

## 💡 Skills Demonstrated
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Label Encoding
- Machine Learning — Regression Modeling
- Model Evaluation and Comparison
- Predictive Analytics

## 📁 Project Structure
```
Health-Insurance-Cost-Prediction
├── PYTHON_PROJECT_Health_Insurance_Cost_Prediction.ipynb
├── README.md
```

## 🚀 Future Improvements
- Hyperparameter Tuning using GridSearchCV
- Cross Validation for better model reliability
- Feature Scaling (StandardScaler) to improve distance-based
  models like KNN
- Feature Selection and importance analysis
- Advanced Ensemble Models — XGBoost, LightGBM
- Model Deployment using Streamlit or Flask

## 👤 Author
**Saurabh Mekhe**
Data Analyst | Python | SQL | Power BI | Machine Learning
LinkedIn: www.linkedin.com/in/saurabh-mekhe-7b5aa6324
GitHub: https://github.com/Saurabh999261
