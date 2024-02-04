# AI-ML-Practical3
**Business Understanding of the Problem:**

The goal of the analysis is to evaluate the performance of four classifiers (K-Nearest Neighbors, Logistic Regression, Decision Trees, and Support Vector Machines) on a Portuguese bank marketing dataset. The dataset contains both categorical and continuous features, and the target variable is binary ('yes' or 'no'), representing whether a client subscribed to a term deposit.


**Repository Structure**

bank_analysis.ipynb: Jupyter notebook containing the code for data cleaning, exploratory data analysis, and model comparisons.
bank-full.csv: dataset.
README.md: This file summarizes the key findings.


**Data Cleaning and Organization:**

The notebook begins by loading the data from the UCI repository, handling missing values, and converting categorical variables into a suitable format for machine learning models. The dataset is then split into training and testing sets, and standardization is applied to the features. The data cleaning process ensures the dataset is ready for model training.


**Interpretation of Descriptive and Inferential Statistics:**

Visualizations are provided for both categorical and continuous variables. The count plots and histograms with kernel density estimates offer insights into the distribution of features concerning the target variable. Descriptive statistics are not explicitly shown, but the visualizations give a sense of feature distributions.


**Findings Section:**

  **Model Performance:**
  
  Each classifier's performance is evaluated using various metrics, including accuracy, precision, recall, F1 score and precision-recall AUC.
  Decision Trees and Logistic Regression show competitive performance across multiple metrics.
  
  **Actionable Items:**
  
  Decision makers could consider Logistic Regression as it shows balanced performance across different metrics.
  Further tuning of hyperparameters might improve the performance of individual models.
  
