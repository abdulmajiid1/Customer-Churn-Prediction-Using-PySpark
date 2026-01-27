# Customer Churn Prediction Using PySpark

A Big Data machine learning project utilizing Apache Spark to predict customer churn in the telecommunications sector. This project demonstrates an end-to-end scalable pipeline—from data ingestion and cleaning to feature engineering and predictive modeling—to identify at-risk customers and key churn drivers.

## 📌 Project Overview

Customer retention is critical in the telecom industry. This project builds a binary classification model to predict whether a customer will "Churn" (leave) or stay. By leveraging **PySpark**, the solution is designed to handle large-scale datasets efficiently, offering insights that can help businesses take proactive retention measures.

## 🚀 Key Features

* **Big Data Tech Stack:** Built entirely using **Apache Spark (PySpark)** for distributed processing.
* **robust Preprocessing:** Handles data veracity issues, missing values, and type casting automatically.
* **Feature Engineering:** Utilizes Spark MLlib for String Indexing, One-Hot Encoding, and Vector Assembly.
* **Predictive Modeling:** Implements **Logistic Regression** to classify customer behavior.
* **Model Evaluation:** Evaluates performance using **AUC (Area Under ROC)**, **Accuracy**, and **Confusion Matrix**.
* **Business Insights:** visualizes feature importance to identify primary risk factors (e.g., Month-to-month contracts, Fiber optic service).

## 📂 Dataset

The project uses the **Telco Customer Churn** dataset.

* **Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn) (or equivalent source).
* **Rows:** ~7,000 customers
* **Features:** 21 attributes including demographics, account information, and service details.

## 🛠️ Installation & Requirements

To run this project locally, you need Python and Apache Spark installed.

1. **Clone the Repository**
```bash
git clone https://github.com/abdulmajiid1/Customer-Churn-Prediction-Using-PySpark.git
cd Customer-Churn-Prediction-Using-PySpark

```


2. **Install Python Dependencies**
```bash
pip install pyspark pandas matplotlib seaborn findspark

```


3. **Setup Spark Environment**
Ensure you have Java (OpenJDK 8 or 11) installed. If you are using Google Colab, the notebook handles the installation of Spark automatically.

## 💻 Usage

1. Open the Jupyter Notebook: `customer_churn_prediction_in_telecom_sector_(2).ipynb`.
2. Ensure the dataset file `WA_Fn-UseC_-Telco-Customer-Churn.csv` is located in the same directory (or update the file path in the notebook).
3. Run the cells sequentially to:
* Initialize the Spark Session.
* Load and clean the data.
* Train the Logistic Regression model.
* Generate predictions and visualize results.



## 📊 Results

The model achieved the following performance metrics on the test dataset:

* **Area Under ROC (AUC):** ~0.86
* **Accuracy:** ~81%

### Key Drivers of Churn identified:

* **High Risk:** Customers with **Month-to-month contracts** and **Fiber Optic** internet service.
* **Low Risk:** Customers with **2-year contracts** and high **Tenure**.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to check the [issues page](https://www.google.com/search?q=https://github.com/abdulmajiid1/Customer-Churn-Prediction-Using-PySpark/issues).

## 📜 License

This project is open-source and available under the [MIT License](https://www.google.com/search?q=LICENSE).

## 👤 Author

**Abdulmajid**

* GitHub: [@abdulmajiid1](https://www.google.com/search?q=https://github.com/abdulmajiid1)
