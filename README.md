📊 Customer Churn Prediction Dashboard
📝 Project Overview

This project focuses on predicting telecom customer churn and visualizing insights through an interactive dashboard. Using Python for data preprocessing, exploratory data analysis (EDA), and machine learning, predictions are stored in MySQL and then visualized in Power BI for business decision-making.

🎯 Objectives


Predict whether a customer is likely to churn.

Analyze key factors driving churn (contract type, payment method, charges).

Provide interactive dashboards to support business retention strategies.

🛠 Tools & Technologies


Python – Data cleaning, EDA, predictive model building

MySQL – Data storage for customers and churn predictions

Power BI – Dashboard creation and visualization

Libraries Used: pandas, numpy, matplotlib, seaborn, scikit-learn, mysql-connector-python

📂 Project Workflow


Data Collection & Preprocessing

Load Telco-Customer-Churn.csv

Handle missing values, encode categorical variables, normalize data

Exploratory Data Analysis (EDA)

Understand churn distribution, identify key drivers

Model Building & Prediction

Train models (Logistic Regression / Random Forest)

Generate churn predictions and store in MySQL

Power BI Dashboard

Connect to MySQL tables (customers, Predicted Churn)

Create DAX measures for churn KPIs

Build interactive dashboard with cards, bar charts, pie chart, and line chart

📊 Dashboard Features


KPIs: Total Customers, Actual Churn %, Predicted Churn %, Model Accuracy

Charts:

Churn by Contract Type

Churn by Payment Method

Churn by Gender (Pie Chart)

Monthly Charges vs Churn

Churn Trend by Tenure

Filters: Gender, Contract, Internet Service, Payment Method

🚀 Outcome


The dashboard enables business users to:

Identify churn-prone customer segments

Monitor churn trends over time

Improve retention strategies based on data-driven insights
