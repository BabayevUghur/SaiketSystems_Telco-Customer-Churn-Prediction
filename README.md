# SaiketSystems_Telco-Customer-Churn-Prediction

Telco Customer Churn Prediction
This project focuses on analyzing customer churn behavior using the Telco Customer Churn Dataset. The goal is to predict whether a customer is likely to churn (leave the service) based on various demographic and service-related features.

Dataset
The dataset contains customer information, including:

Demographics (gender, age, etc.)

Services signed up for (Internet, Online Security, etc.)

Account information (tenure, monthly charges, total charges)

Target variable: Churn (Yes = customer left, No = customer stayed)

Project Workflow
1. Data Loading & Exploration
Loaded data using pandas.

Reviewed structure, missing values, and data types.

Used .info(), .describe(), and value_counts() to understand feature distributions.

2. Exploratory Data Analysis (EDA)
Created visualizations using seaborn and matplotlib:

Count plots of categorical variables (gender, partner, etc.)

Histograms of numerical features like tenure.

Cross-tabulations to analyze churn by different categories.

Identified features that are likely to influence churn.

3. Data Preprocessing
Converted categorical variables to numeric using label encoding and one-hot encoding.

Handled missing values and cleaned the TotalCharges column.

Scaled numerical features if needed.

4. Model Building
Split data into training and test sets.

Trained a classification model using Logistic Regression.

Made predictions on the test data.

5. Model Evaluation
Evaluated model performance using classification metrics:

Accuracy

Precision, Recall, F1-score

Confusion Matrix

ROC AUC Score (used predicted probabilities)

6. Insights
Analyzed prediction results to understand which customers the model predicted as churned or not.

Observed patterns in features like contract type, tenure, dependents, etc., and how they correlate with churn behavior.

Tools & Libraries
Python (pandas, numpy, seaborn, matplotlib, scikit-learn)
