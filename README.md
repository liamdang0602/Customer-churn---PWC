# Project PWC - Tung Dang - Telecom Customer Churn Analysis

## 1.Overview
This repository contains the analysis and deliverables for a PwC Consulting case study focused on Telecom Customer Churn Analysis, conducted by Duc Tung Dang (Liam). The project aims to address high customer churn for a major telecom company using exploratory data analysis (EDA) and a churn prediction model.
## 2.Background & Goals

Objective: Identify key factors driving customer churn and provide data-driven recommendations to enhance retention and profitability.
Approach: Utilizes EDA to study customer demographics and behaviors, and builds a churn prediction model.

## 3.Executive Summary

Key Findings: Customers with short tenure, frequent technical issues, month-to-month contracts, high monthly fees, electronic check payments, paperless billing, and disengagement from ancillary services (e.g., OnlineSecurity, TechSupport) are more likely to churn.
Recommendations: Improve customer service, offer incentives for long-term contracts, adjust pricing strategies, introduce diverse payment options, and use predictive analytics for targeted engagement.

## 4.Data Insights

Dataset: 7,032 customers, with the longest tenure at 72 months and the highest monthly charge at US$118.75.
Churn Rate: Exceeds 25%, with the highest risk within the first 5 months, peaking in the initial 10 months.

## 5.Report Sections

Understanding the Customer Base: Analyzes demographics (age, gender, family structure) and service usage (Internet, Phone, TV).
Customer Segments: Highlights higher churn among seniors, those without dependents/partners, Fiber Optic users, and paperless billing adopters.
Churn Prediction Model: Evaluates Logistic Regression, Decision Tree, Random Forest, and SVM, with Random Forest selected for its balanced performance (accuracy 0.85, F1-score 0.71).
Feature Importance: Tenure (0.16), Technical Tickets (0.15), and Support Ticket Ratio (0.14) are top churn drivers.
Retention Strategies: Includes upgrading infrastructure, enhancing technical staff skills, revising pricing, and promoting loyalty incentives.

## 6.Some Analyzing Graphs

<img width="850" height="547" alt="download" src="https://github.com/user-attachments/assets/3029e0a5-478c-48c0-bef5-52e3a4eae885" />

<img width="1229" height="425" alt="download" src="https://github.com/user-attachments/assets/d62c9d63-82c1-463f-84fa-a15f68f26f76" />

<img width="1211" height="1122" alt="download" src="https://github.com/user-attachments/assets/3b693a5e-00a4-4784-9903-8c9edfb48d66" />

<img width="785" height="314" alt="image" src="https://github.com/user-attachments/assets/45bade0d-e68c-4cee-b635-91c6c247bb23" />

## 7.Library Use
Pandas: Used for data manipulation and analysis.
NumPy: Employed for numerical computations and array operations.
Matplotlib: Utilized for creating static, animated, and interactive visualizations.
Seaborn: Applied for statistical data visualization built on Matplotlib.
Scikit-learn (sklearn): Leveraged for machine learning models and evaluation metrics.

## 8.Usage

Clone the repository and review the PDF report (Project PWC - Tung Dang.pdf) for detailed findings and visualizations.
Explore the data and models (if provided) to replicate or extend the analysis.

## 9.Contact
For inquiries or collaboration, reach out to Duc Tung Dang (Liam) at [insert email or contact method].


