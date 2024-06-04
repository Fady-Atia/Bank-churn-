# Bank-churn-
**Churn Modeling**

* This repository contains a jupyter notebook that analyzes a customer churn dataset and builds models to predict customer churn.

About the Dataset

The dataset contains information about bank customers who have withdrawn their accounts.
The goal is to use this data to build models that can identify customers who are at risk of churning so that the bank can take steps to retain them.
Content

**The jupyter notebook includes the following steps:**
* Importing libraries (numpy, pandas, tensorflow, seaborn, matplotlib)
* Setting the working directory
* Loading the csv data using pandas
* Exploratory data analysis (EDA) including:
* Checking data shape and information
* Dropping unnecessary columns
* Checking for missing values and handling them
* Analyzing unique values in each column
* Visualizing the distribution of features using countplots and histograms
* Checking for correlation between features using heatmaps
**Data preprocessing including:**
* Label encoding categorical variables
* Splitting data into training and testing sets
* Building machine learning models:
* Logistic Regression model
* Artificial Neural Network (ANN) model
* Evaluating model performance using accuracy score
* Normalizing data and evaluating model performance again
* Detecting and handling outliers
* Re-training models with normalized data and outlier-handled data
**Final accuracy **
  * Accuracy ANN ->>  84 %
  * Logistic Regression ->> 81 %  
     
