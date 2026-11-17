# cardiac-diagnostics
Heart Disease Prediction using Machine Learning
This project focuses on predicting the likelihood of heart disease using Machine Learning techniques and patient health data.


## Objectives

- Understand and explore the heart disease dataset.
- Perform data cleaning and preprocessing.
- Handle missing values.
- Encode categorical variables.
- Standardize numerical features.
- Train a Machine Learning model.
- Evaluate model performance.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset Information

- Total Records: 920
- Original Columns: 16
- Input Features Used: 13
- Target Variable: Heart Disease

The target variable is converted into binary classification:

- 0 – No Heart Disease
- 1 – Heart Disease

## Machine Learning Algorithm

**Logistic Regression**

The dataset was divided into:

- Training Data: 80%
- Testing Data: 20%

### Data Preprocessing

The following techniques were used:

- SimpleImputer for handling missing values.
- OneHotEncoder for categorical variables.
- StandardScaler for numerical features.
- ColumnTransformer for preprocessing.
- Pipeline for combining preprocessing and model training.

## Model Performance

| Evaluation Metric | Score |
|---|---:|
| Accuracy | 84.24% |
| Precision | 84.11% |
| Recall | 88.24% |
| F1-Score | 86.12% |

## Project Workflow

1. Dataset Loading
2. Data Exploration
3. Data Cleaning
4. Missing Value Handling
5. Categorical Encoding
6. Feature Standardization
7. Train-Test Splitting
8. Logistic Regression Model Training
9. Model Evaluation
10. Confusion Matrix Visualization

## Project Structure

```text
cardiac-diagnostics/
│
├── heart_disease.ipynb
├── README.md
├── requirements.txt
├── data/
│   └── heart_disease_uci.csv
└── images/
    └── confusion_matrix.png
```

## How to Run the Project

1. Clone this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Load the dataset using the correct file path.
5. Run all notebook cells.

## Disclaimer

This project is developed for educational purposes only. It is not intended to provide medical diagnoses or replace professional medical advice.

## Author

**Pranav Raj**

B.Tech – Computer Science and Engineering



