# Machine-Learning-Project

# Dataset
The dataset used in this project tracks user engagement and learning activity metrics on an online platform. It includes the following features:
# Features:
student_country: The country of the student (e.g, "US", "SG").
days_on_platform: Total number of days the student has been active on the platform.
minutes_watched: Total minutes spent watching content on the platform.
courses_started: Number of courses started by the student.
practice_exams_started: Number of practice exams the student has started.
practice_exams_passed: Number of practice exams the student passed.
minutes_spent_on_exams: Time spent on exams in minutes.
purchased: Binary indicator of whether the student made a purchase (1 = Yes, 0 = No).

# Objective:
The primary goal is to predict whether a user will make a purchase (purchased) based on their activity on the platform.

# Workflow
# 1. Data Loading and Exploration
Imported the dataset using pandas.
Inspected the dataset for structure, missing values, and statistical summaries.
# 2. Data Preprocessing
Handled missing values using appropriate imputation techniques.
Encoded categorical variables using methods such as one-hot encoding or label encoding.
Scaled numerical features to ensure all features contribute equally to the model.
# 3. Exploratory Data Analysis (EDA)
Visualized data distribution and relationships between features using matplotlib and seaborn.
Identified correlations and potential multicollinearity issues.
# 4. Model Building
Split the dataset into training and testing sets.
Built baseline machine learning models using scikit-learn, such as:
Linear Regression
Decision Trees
Random Forest
Support Vector Machines (SVM)
# 5. Model Evaluation
Evaluated model performance using metrics such as:
Classification: Accuracy, Precision, Recall, F1-Score
Regression: Mean Squared Error (MSE), R-squared
Plotted confusion matrices and learning curves.
# 6. Hyperparameter Tuning
Improved model performance through hyperparameter optimization techniques like Grid Search and Random Search.

