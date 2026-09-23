Customer Churn Prediction using Machine Learning

An end-to-end machine learning project focused on understanding customer
behavior and predicting customer churn using customer usage and
subscription data.

Problem Statement

Customer churn is a major challenge for subscription-based businesses.
This project focuses on predicting whether a customer is likely to churn
based on customer usage patterns and subscription details.

Dataset

The dataset contains customer-level information including:

Age

Gender

Location

Subscription Length

Monthly Bill

Total Usage

Churn Status (target variable)

Note: The dataset is used for educational purposes.

Project Approach

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Encoding categorical variables

Feature selection

Logistic Regression model training

Model evaluation using accuracy and confusion matrix

Key Insights

Monthly bill and total usage are strong indicators of churn.

Longer subscription duration is associated with lower churn
probability.

Customer behavior provides more useful signals than demographics in
this analysis.

Model Performance

Model: Logistic Regression

Accuracy: Approximately 50%

Evaluation: Accuracy and confusion matrix

Focus: Interpretability and business understanding

The reported performance is included as documented in the original
project. The model should therefore be interpreted as an educational
analysis rather than a production-ready churn prediction system.

Business Relevance

The analysis demonstrates how customer usage, billing, and subscription
information can be used to understand churn patterns and support
retention-related business decisions.

How to Run

Install the required dependencies:

pip install -r requirement.txt

Open the Jupyter Notebook:

jupyter notebook "Customer Churn Prediction.ipynb"

Project Files

Customer Churn Prediction.ipynb --- Jupyter Notebook containing
the analysis and machine learning workflow

Project Report.pdf --- Project report

customer_churn_large_dataset.xlsx --- Dataset

requirement.txt --- Required Python packages

README.md --- Project documentation

Author

Bholanath Mishra
