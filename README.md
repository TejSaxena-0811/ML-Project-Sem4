1. Project Overview
This project analyzes telecom customer data to predict the likelihood of customer churn using machine learning models. The goal is to help telecom providers identify customers at risk of leaving and take preventive actions.

2. Dataset
Source: Telco Customer Churn dataset (Kaggle link)

Features: Includes customer demographics, service usage details, contract information, billing data, and churn status.

3. Key Steps
Data Preprocessing
Converted column data types and handled missing values

Dropped irrelevant columns like customerID

Encoded categorical variables using label encoding and one-hot encoding

Scaled numerical features to standardize values

Exploratory Data Analysis (EDA)
Analyzed class imbalance in churn labels

Visualized churn impact based on contract type, tenure, and charges

Checked correlations between features

Model Building
Trained and evaluated models:

Logistic Regression

Random Forest Classifier

Evaluation
Used accuracy score, confusion matrix, and classification report

Random Forest outperformed Logistic Regression

Plotted feature importance to understand key churn factors

4. Results
Best Performing Model: Random Forest Classifier

Top Predictors of Churn:

Contract type

Monthly charges

Tenure

5. Libraries Used
pandas

numpy

matplotlib

seaborn

scikit-learn
