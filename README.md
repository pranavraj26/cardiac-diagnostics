# cardiac-diagnostics
Heart Disease Prediction using Machine Learning
This project uses Machine Learning to predict the likelihood of heart disease based on patient health information
Objectives

Explore and understand the heart disease dataset.

Perform data cleaning and preprocessing.

Handle missing values.

Encode categorical features.

Standardize numerical features.

Train a Machine Learning classification model.

Evaluate model performance.

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

Dataset Information

Total records: 920

Original columns: 16

Input features used: 13

Target: Heart Disease (0 or 1)

The target was converted into binary classification:

0 – No Heart Disease

1 – Heart Disease

Machine Learning Algorithm

Logistic Regression

The dataset was divided into:

Training data: 80%

Testing data: 20%

Data preprocessing was performed using:

SimpleImputer

OneHotEncoder

StandardScaler

ColumnTransformer

Pipeline

Model Performance

Evaluation Metric

Result

Accuracy

84.24%

Precision

84.11%

Recall

88.24%

F1-score

86.12%

Project Workflow

Dataset loading and exploration

Data cleaning

Missing value handling

Categorical encoding

Feature standardization

Train-test splitting

Logistic Regression model training

Model evaluation

Confusion matrix visualization
