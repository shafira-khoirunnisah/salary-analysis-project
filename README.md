## 📊 Salary Analysis & Prediction Project


## 📌 Overview

This project explores the factors influencing salary and builds predictive models using machine learning techniques. The analysis focuses on identifying key drivers such as experience, education, company characteristics, and location.


## 🎯 Objectives
- Analyze salary distribution and trends
- Identify key factors affecting salary
- Build a predictive model for salary estimation
- Compare performance of different machine learning models


## 📂 Dataset

The dataset contains job-related information, including:
- Job title
- Experience level
- Education level
- Industry
- Company size
- Location
- Remote work status
- Salary (target variable)


## 🔍 Exploratory Data Analysis

Key findings:
- Salary follows a near-normal distribution with slight positive skew
- Experience has a strong positive relationship with salary
- Higher education levels correspond to higher median salaries
- Location and company size significantly impact salary
- The US and enterprise companies offer the highest compensation


## 📊 Key Visualizations

### Salary Distribution
![Salary Distribution](https://github.com/shafira-khoirunnisah/salary-analysis-project/blob/510045668601348aa65145bf2e16232374cf8f94/images/Salary%20Distribution.png)

### Salary vs Experience
![Salary vs Experience](https://github.com/shafira-khoirunnisah/salary-analysis-project/blob/dd49e3901b0098f549d4bc73707852dc0d78b3e8/images/Salary%20vs%20Experience.png)

### Salary by Education
![Salary by Industry](images/Salary_vs_Education.png)


## 🤖 Modeling

Two models were used:
1. Linear Regression
   - MAE: ~5,436
   - RMSE: ~7,125
   - R2: ~0.963
     
2. Random Forest
   - MAE: ~5,693
   - RMSE: ~7,375
   - R2: ~0.961

## 📈 Key Insights
- Linear Regression outperformed Random Forest, indicating largely linear relationships
- Experience is the most influential factor in salary prediction
- Location plays a major role, highlighting geographic disparities
- Company size and education level also contribute significantly

## ⚠️ Limitations
- The dataset appears highly structured, which may not reflect real-world complexity
- Some variables (e.g., skills count, certifications) show weak influence

## 🚀 Tools & Technologies
- Python (Pandas, NumPy)
- Data Visualization (Matplotlib, Seaborn)
- Machine Learning (Scikit-learn)

## 📌 Conclusion

This project demonstrates how data analysis and machine learning can be used to understand salary dynamics. While the model performs well, future work could include more complex and realistic datasets for improved generalization.
