Summary of Retinopathy Disease Prediction Using Machine Learning

1. Data Overview
The dataset used for predicting retinopathy consists of 6,000 patient records, with the following features:

Age: The patient's age.

Systolic Blood Pressure: The pressure in the arteries when the heart beats.

Diastolic Blood Pressure: The pressure in the arteries when the heart rests between beats.

Cholesterol: The cholesterol level.

Has Retinopathy: The target variable indicating the presence (1) or absence (0) of retinopathy.
The data was clean, with no duplicates or missing values.

2. Exploratory Data Analysis (EDA)
Several visualizations were created to understand the distribution of features and their relationships:
Histograms were plotted to show the distributions of age, systolic and diastolic blood pressure, and cholesterol.
A correlation matrix was used to examine the relationships between the features.
Scatter plots were generated to visualize the relationships between age, blood pressure, cholesterol, and the presence of retinopathy.
A count plot and a pie chart illustrated the distribution of the target variable (has_retinopathy), showing the proportion of patients with and without retinopathy.

4. Model Building
Four machine learning models were built and evaluated:

Logistic Regression

Support Vector Classifier (SVC)

Decision Tree Classifier

Random Forest Classifier

The data was split into training and testing sets (70% training, 30% testing). Feature scaling was applied using StandardScaler to normalize the data for models like Logistic Regression and SVC.

4. Model Evaluation
The models were evaluated based on their accuracy scores on the test set:

Logistic Regression: 50.2%

SVC: 49.60%

Decision Tree: 49.70%

Random Forest: 48.80%

A bar chart was created to compare the accuracy of each model, with Logistic Regression performing slightly better than the others.
