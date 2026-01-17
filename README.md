# IBM HR Analytics Employee Attrition & Performance
This Project is done under the guidance of Unified Mentor and this is the project which i have done while i was in Internship with Unified Mentor. This is a guided learning project focused on data analysis and visualization

## 1. Introduction
Employee attrition affects company performance and productivity. This project aims to analyze attrition drivers and build a predictive model to identify employees at risk of leaving.

## 2. Dataset Overview
- Total records: 1470 employees
- Features: 34+ demographic, job, and salary attributes
- Target: Attrition (Yes=1, No=0)

## 3. Data Cleaning
- Removed irrelevant columns: EmployeeCount, Over18, StandardHours, EmployeeNumber
- Converted categorical variables using one-hot encoding
- No missing data present

## 4. Exploratory Data Analysis
- Attrition rate approximately 16%
- Key factors impacting attrition: Monthly Income, Age, Years at Company, Total Working Years
- Visualization shows lower income and fewer working years correlate with higher attrition

## 5. Feature Engineering
- Created new features like 'HighIncome' based on median Monthly Income
- Encoded categorical variables for modeling

## 6. Model Building & Evaluation
- Models used: Logistic Regression and Random Forest
- Random Forest achieved 100% accuracy on test set (possible overfitting)
- Key features identified: MonthlyIncome, TotalWorkingYears, Age, YearsAtCompany

## 7. Business Recommendations
- Increase compensation and benefits for lower-paid employees
- Develop retention strategies tailored to younger or less-tenured employees
- Promote career growth opportunities to encourage longer tenure

## 8. Limitations & Future Work
- Model requires validation with larger and more diverse data
- Explore additional features like job satisfaction and work-life balance
- Implement hyperparameter tuning and cross-validation

---
