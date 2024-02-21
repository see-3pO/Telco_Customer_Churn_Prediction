# Telco_Customer_Churn_Prediction

This project focuses on predicting customer churn for a telecommunications (telco) company. Customer churn refers to the phenomenon where customers stop using a company's services. Predicting churn is crucial for businesses as it allows them to identify and possibly retain customers at risk of leaving.

## Steps in the Project:

1. **Importing Libraries:** Necessary Python libraries such as Pandas, NumPy, Matplotlib, and Scikit-learn were imported to facilitate data manipulation, visualization, and modeling.

2. **Loading the Dataset:** The telco company's dataset containing information about customers was loaded into the project environment. This dataset likely includes features such as customer demographics, service usage, and churn status.

3. **Exploratory Data Analysis (EDA):** Exploring the dataset to understand its structure, identify patterns, and gain insights into customer behavior and characteristics.

4. **Handling Outliers using IQR Method:** Outliers, if present, were identified and managed using the Interquartile Range (IQR) method to prevent them from skewing the analysis and modeling process.

5. **Cleaning and Transforming the Data:** Data cleaning techniques were applied to handle missing values, inconsistencies, and other data quality issues. Additionally, data transformations may have been performed to prepare the dataset for modeling.

6. **Modeling and Prediction:**

  * Logistic Regression: Building a logistic regression model to predict customer churn based on selected features.
  * Support Vector Classifier: Utilizing a Support Vector Classifier (SVC) to predict churn, which is effective in handling high-dimensional data.
  * Decision Tree Classifier: Constructing a decision tree-based classifier to predict churn by recursively partitioning the feature space.
  * KNN Classifier: Employing a K-Nearest Neighbors (KNN) classifier to predict churn based on the similarity of customers' features.

Credits: This was for the most part a guided project from [Youtube](https://youtu.be/1nKOVQyrUqI?si=znnGU_dGGQi65-TA).
Hope to continue making cool projects in the data science space.
