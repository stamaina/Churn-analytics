# Customer Churn Analysis - SyriaTel
## Business Understanding
SyriaTel a telecommunications company faces a significant challenge with customer churn, which undermines revenue and operational efficiency. Retaining existing customers is crucial, as acquiring new ones is often more expensive. To tackle this issue, there is need to analyze the key factors influencing churn and develop a predictive model to identify at-risk customers.
## Problem statement
By examining customer behavior, usage patterns, and service quality, insights that drive effective retention strategies can be uncovered. It's vital to assess service experiences, address customer complaints, and ensure competitive pricing. Creating a predictive model will allow us to categorize churn risks and engage proactively with at-risk customers through tailored offers and support.
## Key Findings

## Exploratory Data Analysis (EDA) Results

Customers with higher customer service calls are more likely to churn, indicating dissatisfaction.

Total day minutes and total day charge are strong indicators of churn, suggesting pricing concerns.

Customers with an international plan have a significantly higher likelihood of churning.

## Chi-Square Test Results

Voice Mail Plan vs. Churn: Chi-Square = 34.13, p-value = 5.15e-09 (Statistically significant)

International Plan vs. Churn: Chi-Square = 222.57, p-value = 2.49e-50 (Highly significant)
## Machine Learning Models

## Model Evaluation Summary

Random Forest: Best model with 91.4% accuracy and an AUC of 0.888, effectively differentiating churn cases.

Decision Tree: High accuracy (0.918) but lower AUC (0.774), suggesting potential overfitting.

SVM: AUC of 0.827, offering a fair balance between precision and recall.

Logistic Regression: AUC of 0.794 but struggles with recall, requiring further improvements.

KNN: Weakest model with poor recall and F1-score, not suitable for churn prediction.

## Recommendations

Improve Customer Service Efficiency: Implement AI-driven chatbots and self-service portals to resolve common issues faster.

Personalized Retention Offers: Identify high-risk customers and provide tailored discounts or loyalty plans.

Optimize International Plan Strategy: Review pricing and offer exclusive deals for international plan subscribers.

Leverage Data-Driven Decision-Making: Continuously refine machine learning models and conduct A/B testing to improve retention strategies.

## Conclusion
By leveraging data-driven insights, SyriaTel can better predict customer churn and implement effective strategies to improve retention. The Random Forest model emerged as the best predictive model, and addressing service dissatisfaction and pricing concerns will be key to reducing churn.

## Files Included

phase_3_project.ipynb: Jupyter Notebook for data exploration and visualization also containing the machine learning models and performance evaluation.

phase_3_project.pdf: a pdf for data exploration and visualization also containing the machine learning models and performance evaluation.

presentation.pdf: Presentation summarizing the analysis and findings.

README.md: This document.
