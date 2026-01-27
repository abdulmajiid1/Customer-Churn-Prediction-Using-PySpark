Customer Churn Prediction Using PySpark
A Big Data machine learning project utilizing Apache Spark to predict customer churn in the telecommunications sector. This project demonstrates an end-to-end scalable pipeline—from data ingestion and cleaning to feature engineering and predictive modeling—to identify at-risk customers and key churn drivers.

📌 Project Overview
Customer retention is critical in the telecom industry. This project builds a binary classification model to predict whether a customer will "Churn" (leave) or stay. By leveraging PySpark, the solution is designed to handle large-scale datasets efficiently, offering insights that can help businesses take proactive retention measures.

🚀 Key Features
Big Data Tech Stack: Built entirely using Apache Spark (PySpark) for distributed processing.

robust Preprocessing: Handles data veracity issues, missing values, and type casting automatically.

Feature Engineering: Utilizes Spark MLlib for String Indexing, One-Hot Encoding, and Vector Assembly.

Predictive Modeling: Implements Logistic Regression to classify customer behavior.

Model Evaluation: Evaluates performance using AUC (Area Under ROC), Accuracy, and Confusion Matrix.

Business Insights: visualizes feature importance to identify primary risk factors (e.g., Month-to-month contracts, Fiber optic service).

📂 Dataset
The project uses the Telco Customer Churn dataset.

Source: Kaggle - Telco Customer Churn (or equivalent source).

Rows: ~7,000 customers

Features: 21 attributes including demographics, account information, and service details.
