# Predicting Employee Attrition Using Machine Learning Algorithms

## Project Overview
This project aims to predict employee attrition by analyzing key factors influencing employee turnover. Using machine learning algorithms, the goal is to provide actionable insights for organizations to reduce attrition rates and improve employee satisfaction. The dataset used in this project is sourced from Kaggle and contains over 51,000 employee records with 35 attributes.

## Features and Dataset
- **Dataset Source**: [Kaggle HR Employee Attrition Dataset](https://www.kaggle.com/datasets/whenamancodes/hr-employee-attrition)
- **Number of Records**: 51,450
- **Attributes**: 35 features, including age, job satisfaction, income, marital status, overtime, and distance from home.

### Key Research Questions
1. What are the major factors contributing to employee attrition?
2. How can the relationships between these factors be quantified and analyzed?
3. Which machine learning algorithms perform best for predicting attrition?

## Workflow
The project follows these key steps:

1. **Data Preprocessing**:
    - Cleaning the dataset by removing irrelevant columns, handling missing values, and converting categorical columns into numerical ones.
    - Splitting the dataset into training and test sets.

2. **Data Analysis**:
    - Visualizing key trends and relationships using scatter plots, box plots, and ggplot.
    - Identifying high-attrition job roles and correlating them with factors like income and job satisfaction.

3. **Modeling**:
    - Algorithms used: Logistic Regression, Naïve Bayes, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Decision Tree.
    - Model evaluation based on accuracy, precision, and recall.

4. **Model Comparison**:
    - Logistic Regression and Naïve Bayes emerged as the best-performing models with an accuracy of 85%.

5. **Insights and Recommendations**:
    - Identified key factors influencing attrition: low monthly income, overtime, distance from home, and job satisfaction.
    - Recommended HR interventions based on model insights.

## Results
- Logistic Regression: 85% accuracy
- Naïve Bayes: 84% accuracy
- SVM: 83% accuracy
- Key insight: Job roles with lower income and satisfaction have the highest attrition rates.

## Tools and Technologies
- **Programming Languages**: Python
- **Visualization Tools**: ggplot, Matplotlib
- **Libraries**: Scikit-learn, Pandas, NumPy
- **Algorithms**: Logistic Regression, Naïve Bayes, SVM, KNN
