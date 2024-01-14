
Objective:

Predict who is likely to cancel their credit card by building and evaluating a classification model.
Steps Performed:

Exploratory Data Analysis (EDA):

Understanding the dataset's structure and content.
Exploring data types, checking for duplicate values, and handling missing values.

Data Preparation:

Removing unnecessary columns (e.g., CLIENTNUM).
Encoding categorical variables.
Handling missing values (using mode imputation).
Model Building:

Using logistic regression as the classification model.
Training the model on the prepared data.
Performance Evaluation:

Assessing the model's performance on both training and test datasets.
Calculating metrics such as accuracy, precision, recall, and confusion matrix.
Model Selection:
Analyzing the coefficients of the logistic regression model to understand the impact of features on attrition.

Data Discovery:
Conducting exploratory data analysis, including visualizations (e.g., boxplots, bar charts, heatmap) to understand the distribution of variables and relationships.
Data Description:
Providing descriptive statistics and summaries for numerical and categorical columns.
Key Components and Concepts:

Dataset Characteristics:
Client information, including age, gender, education level, marital status, income category, card category, etc.
Target variable: Attrition_Flag (customer activity indicating if the account is closed or not).
Modeling Techniques:
Logistic Regression for binary classification.

Evaluation Metrics:
Accuracy, Precision, Recall, Confusion Matrix.

Data Exploration:
Understanding the distribution of variables using visualizations.
Analyzing correlations between variables.

Data Preprocessing:
Handling missing values (imputation).
Encoding categorical variables.

Outlier Analysis:
Identifying and handling outliers using IQR (Interquartile Range).
Performance Evaluation:
Assessing the model's ability to predict customer attrition.
Feature Importance:
Analyzing logistic regression coefficients to identify important features.


Outcome:
The model's performance metrics, including accuracy, precision, recall, and insights into key features impacting attrition.
