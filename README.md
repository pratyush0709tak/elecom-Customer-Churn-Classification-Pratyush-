# Telecom-Customer-Churn-Classification-Pratyush-

Customer Churn Analysis for Telecom Company

Project Overview

This project aims to analyze customer churn for a telecom company. Using customer data over a four-month period, the analysis focuses on identifying high-risk customers likely to churn, building predictive models to classify churn probability, and recommending business strategies for customer retention.

Objectives

	•	Business Objective: Identify high-risk customers to enable proactive retention strategies.
	•	Technical Objective: Build predictive models to classify customers based on churn risk, leveraging data from customer usage patterns and behaviors.

Files in Repository

	•	Telecom Customer Churn Classification (Pratyush).ipynb: Jupyter Notebook containing code for data preprocessing, feature engineering, model training, evaluation, and feature importance analysis.
	•	Telecom Customer Churn Classification (Pratyush).pptx: PowerPoint presentation summarizing both technical and business insights from the analysis.
	•	README.md: Overview of the project, file contents, and instructions for replicating the analysis.

Dataset Description

	•	Period Covered: June to September 2014
	•	Size: 99,999 records with monthly usage details
	•	Attributes: Includes customer information on calls, SMS, recharge, and data usage.
	•	Churn Definition: Customers with no calls or data usage in September are labeled as “churned.”

Methodology

	1.	Data Preparation:
	•	Filtered high-value customers based on the 70th percentile of recharge amounts.
	•	Tagged churners based on activity in the final month (September).
	•	Removed all September data from the training set to simulate real-world conditions.
	2.	Modeling Approach:
	•	Used SMOTE to handle class imbalance in the data.
	•	Built two models: Logistic Regression for interpretability and Random Forest for accuracy and feature importance insights.
	3.	Evaluation:
	•	Evaluated models on metrics including Precision, Recall, and F1-Score.
	•	Identified the top features influencing churn, including recharge amount, outgoing minutes, and data usage patterns.

Key Findings

	•	Top Predictors:
	•	Monthly recharge amount in good and action phases.
	•	Outgoing call minutes and data usage trends.
	•	Notable drop in usage between July and August as an indicator of churn risk.

Business Recommendations

	•	Retention Strategies:
	•	Target high-risk customers with personalized offers and discounts.
	•	Improve service quality based on customer needs in the Action phase.
	•	Customer Engagement:
	•	Enhance frequently used services and conduct regular engagement during dissatisfaction periods to preempt churn.

Pratyush Srivastava
