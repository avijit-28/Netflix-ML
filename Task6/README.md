# Task 6 (Advanced) – Netflix Content Success Analytics Engine

## Description
End-to-end machine learning solution that analyzes content patterns and generates intelligent, automated business insights.

## Workflow
1. Performed advanced feature engineering (content age, genre count, multi-country flag, proxy "broad reach" target)
2. Built and trained 4 models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting
3. Compared model performance using Accuracy, Precision, Recall, F1 Score
4. Applied hyperparameter tuning via GridSearchCV to the best-performing model
5. Generated automated, plain-English business insights from feature importance and group trends
6. Presented findings in a 2x2 visual dashboard report (`netflix_analytics_report.png`)

## Note on Target Variable
This dataset has no real "success" metric (e.g. views, ratings). A proxy target (`broad_reach`) was engineered based on genre breadth and multi-country distribution to demonstrate the full ML pipeline end-to-end.

## Skills Demonstrated
Machine Learning Pipeline Development, Feature Engineering, Model Optimization, MLOps Fundamentals

## How to Run
Open the notebook in Google Colab, upload `Dataset.csv`, and run all cells in order.
