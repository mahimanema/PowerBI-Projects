# Loan Risk Analysis & Loan Approval Prediction

## Project Overview

The Loan Risk Analysis & Loan Approval Prediction project is an end-to-end analytics solution developed using Power BI and Python to analyze loan applications, evaluate applicant financial strength, identify key factors influencing loan approval and rejection decisions, and predict loan eligibility using Machine Learning.

The primary objective of this project is to transform raw loan application data into meaningful business insights related to applicant eligibility, creditworthiness, financial behavior, and asset-based risk analysis while building a predictive model capable of forecasting loan approval outcomes. The dashboard analyzes important financial indicators such as income, loan amount, loan term, CIBIL score, residential assets, commercial assets, luxury assets, bank assets, and applicant dependency details to better understand applicant profiles, lending patterns, and financial risk.

In addition to interactive business intelligence reporting, the project includes a complete Machine Learning workflow involving data preprocessing, label encoding, Random Forest model development, feature importance analysis, model evaluation, and prediction on new applicant data. This project was designed to provide both descriptive and predictive analytics through structured dashboards and machine learning techniques.

---

## Business Problem

Financial institutions process a large number of loan applications and must evaluate applicant eligibility, repayment capability, financial stability, and credit risk before approving loans.

Manually analyzing applicant financial profiles and predicting loan approval decisions can be complex and time-consuming. This project simplifies both analytical reporting and predictive decision-making by combining an interactive Power BI dashboard with a Machine Learning model. The dashboard improves visibility into applicant profiles, approval trends, financial strength, asset distribution, and risk categories, while the predictive model estimates loan approval outcomes for new applicants based on historical financial and credit-related information.

The solution enables better understanding of lending behavior, supports risk assessment, and assists data-driven decision-making through descriptive and predictive analytics.

---

## Dashboard Pages

### 1. Executive Summary

The Executive Summary page provides a centralized overview of overall loan application performance and applicant distribution. This section was designed to give a quick understanding of approval trends, rejection patterns, applicant categories, and overall lending activity through high-level KPI reporting and summary visualizations. It helps simplify large volumes of loan data into an easily understandable business overview for quick decision-making and performance monitoring.

### 2. Financial Analysis

The Financial Analysis page focuses on evaluating applicant financial behavior and lending trends using key financial indicators such as income, loan amount, loan term, and CIBIL score. This section helps identify financial patterns influencing loan approvals and rejections while providing deeper visibility into applicant repayment capability and financial stability. The analysis supports better understanding of financial relationships and lending behavior through interactive visual reporting.

### 3. Asset Analysis

The Asset Analysis page was designed to evaluate applicant financial strength using different asset categories, including residential, commercial, luxury, and bank assets. This section helps analyze asset distribution, compare applicant asset profiles, and understand how asset ownership impacts loan eligibility and approval behavior. The dashboard provides a structured view of applicant financial capacity and strengthens the overall business storytelling of the project.

### 4. Risk Analysis

The Risk Analysis page focuses on evaluating applicant creditworthiness and identifying high-risk applicant categories using CIBIL score and income-based segmentation. This section helps analyze approval and rejection behavior across different risk groups and provides better visibility into applicant financial risk patterns. The analysis supports more informed lending decisions by simplifying risk identification through interactive and business-focused reporting.

---

## Machine Learning Workflow

The Machine Learning component extends the analytical capabilities of the project by predicting loan approval using applicant financial, credit, and asset information. The workflow includes data preprocessing, label encoding of categorical variables, train-test splitting, Random Forest model training, prediction, model evaluation using Accuracy Score, Confusion Matrix, and Classification Report, feature importance analysis, model persistence using Joblib, and prediction on **150 new applicants** from an external Excel dataset.

The Random Forest model achieved an overall prediction accuracy of **97.78%**, demonstrating strong predictive performance for loan approval classification.

---

## Tools & Technologies Used

### Business Intelligence
- Power BI
- Power Query
- Data Visualization
- Dashboard Development
- Business Intelligence
- Financial Analysis

### Machine Learning
- Python
- Pandas
- NumPy
- Scikit-learn
- Random Forest Classifier
- Joblib
- Machine Learning

---

## Key Insights

- Identified approval and rejection trends across different applicant categories.
- Analyzed relationships between income, assets, CIBIL score, loan amount, and loan term.
- Evaluated applicant financial strength using asset-based analysis.
- Segmented applicants into different risk categories based on financial and credit-related factors.
- Identified **CIBIL Score** as the most influential feature affecting loan approval through feature importance analysis.
- Developed a Random Forest Machine Learning model achieving **97.78% prediction accuracy**.
- Successfully predicted loan approval outcomes for **150 new applicants** using a saved Machine Learning model.
- Improved visibility into applicant eligibility patterns and lending behavior through interactive reporting and predictive analytics.

---

## Features

### Power BI Dashboard

- Multi-page interactive dashboard design
- KPI cards for financial and risk analysis
- Interactive filters and slicers for dynamic reporting
- Financial trend analysis and applicant segmentation
- Asset distribution and risk category analysis
- Structured and business-focused visual storytelling
- Consistent dashboard theme and navigation design

### Machine Learning

- Data preprocessing pipeline
- Label encoding
- Random Forest prediction model
- Model evaluation metrics
- Feature importance visualization
- Model saving and loading using Joblib
- Prediction on external Excel data
- Export of prediction results

---

## Conclusion

This project demonstrates an end-to-end loan analytics solution by combining Power BI dashboards with Machine Learning to analyze loan applications and predict loan approval outcomes. The dashboard simplifies complex financial and applicant-related data through interactive reporting, while the Random Forest model predicts loan approval using applicant financial, credit, and asset information with an accuracy of **97.78%**.

The trained model was successfully saved and later used to predict loan approval for **150 new applicants** from an external Excel dataset, demonstrating its practical application on unseen data. The project highlights the combined use of business intelligence, data visualization, and predictive analytics to support data-driven lending decisions, evaluate applicant financial strength, identify risk patterns, and improve the overall loan assessment process.
