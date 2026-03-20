# DataAnalytics-Project-
# Machine Learning Projects: Data Analysis & Predictive Modeling

## Overview
This repository documents three machine learning projects exploring fundamental concepts: exploratory data analysis, classification modeling for customer churn, and regression modeling for insurance claim prediction.

---

## Task 1: Exploring and Visualizing a Simple Dataset (Iris Dataset)

### Objective
Load, summarize, and visualize the Iris dataset to understand data structure and relationships between variables.

### Approach
- Loaded the dataset using pandas and inspected its structure (shape, columns, head)
- Created scatter plots to analyze relationships between sepal and petal measurements
- Generated histograms to examine distribution patterns across species
- Used box plots to identify outliers and spread of values

### Key Insights
- Setosa species is distinctly separable from Versicolor and Virginica
- Petal length and width are the most discriminative features
- Minimal outliers present, indicating a clean dataset
- Strong positive correlation exists between petal length and petal width

---

## Task 3: Customer Churn Prediction (Bank Customers)

### Objective
Build a classification model to predict which bank customers are likely to churn and identify key influencing factors.

### Approach
- Cleaned and prepared the dataset by removing unnecessary columns
- Encoded categorical features (geography, gender) using Label Encoding
- Trained Random Forest and Logistic Regression classification models
- Evaluated model performance using accuracy, confusion matrix, and classification report
- Added MAE and RMSE metrics to evaluate probability predictions
- Analyzed feature importance to understand churn drivers

### Key Insights
**Top Churn Factors:**
- Age (customers over 50 show higher churn rates)
- Account balance (zero or very high balance increases churn risk)
- Credit score (lower scores correlate with higher churn)
- Geography (German customers have highest churn rate)

**Model Performance:**
- Random Forest achieved ~85% accuracy
- MAE of ~0.12 and RMSE of ~0.28 for probability predictions
- Model performs better at identifying non-churners than churners

**Recommendations:**
- Target high-risk groups with retention programs
- Focus retention efforts on German customers and age group 40-60
- Monitor customers with sudden balance changes

---

## Task 4: Predicting Insurance Claim Amounts

### Objective
Estimate medical insurance claim amounts based on personal data using linear regression.

### Approach
- Preprocessed data by encoding categorical variables (sex, smoker, region)
- Scaled numerical features for optimal model performance
- Trained a Linear Regression model to predict insurance charges
- Visualized how BMI, age, and smoking status impact charges
- Evaluated model using MAE (Mean Absolute Error) and RMSE (Root Mean Square Error)

### Key Insights
**Influential Factors:**
- Smoking status is the strongest predictor (smokers pay 3-4x higher premiums)
- Age shows strong positive correlation with charges
- BMI has moderate impact on insurance costs
- Number of children shows slight positive correlation

**Model Performance:**
- Testing MAE: ~$4,200 (average prediction error)
- Testing RMSE: ~$6,000 (penalizes larger errors)
- Model explains approximately 75-80% of variance in charges

**Key Observations:**
- Smokers show dramatically higher charges across all age groups and BMI levels
- Combined effect of smoking with age or BMI creates exponential cost increases
- Non-smokers maintain relatively stable charges regardless of BMI

---

## Skills Demonstrated

| Task | Skills |
|------|--------|
| Task 1 | Data loading, pandas operations, data summarization, matplotlib & seaborn visualization |
| Task 3 | Categorical encoding, classification modeling, feature importance analysis, model evaluation |
| Task 4 | Regression modeling, feature correlation, MAE & RMSE evaluation, visualization |

---

## Tools & Libraries
- Python
- pandas (data manipulation)
- scikit-learn (modeling, preprocessing, evaluation)
- matplotlib & seaborn (visualization)
- numpy (numerical operations)
