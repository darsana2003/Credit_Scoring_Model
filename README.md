# Credit Scoring Model

## Project Overview
This project focuses on predicting the credit risk of loan applicants using Machine Learning classification algorithms.

The model analyzes customer financial and personal information to determine whether the applicant belongs to:

- Good Credit Risk
- Bad Credit Risk

This project helps financial institutions make better loan approval decisions.

---

# Dataset Information

- Dataset Name : German Credit Dataset
- Target Column : Risk

## Target Classes
- Good → Customer is likely to repay the loan
- Bad → Customer has higher credit risk


# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


# Project Workflow

## 1. Data Collection
The dataset was collected from Kaggle and loaded using Pandas.

### Dataset Features
- Age
- Sex
- Job
- Housing
- Saving accounts
- Checking account
- Credit amount
- Duration
- Purpose
- Risk


## 2. Data Exploration

The following exploratory steps were performed:

- Checked dataset shape
- Viewed column names
- Identified missing values
- Checked duplicate records
- Generated statistical summary


## 3. Exploratory Data Analysis (EDA)

EDA was performed to understand customer behavior and feature relationships.

### Visualizations Used

#### Numerical Analysis
- Histograms
- Distribution plots
- Boxplots

#### Categorical Analysis
- Count plots
- Risk distribution plots

#### Relationship Analysis
- Correlation heatmap
- Scatter plots
- Pair plots


## 4. Data Cleaning

The following preprocessing steps were applied:

- Missing value handling
- Removed unnecessary columns
- Checked inconsistent values
- Removed extra spaces
- Standardized categorical values


## 5. Outlier Detection and Removal

- Outliers were identified using Boxplots
- The IQR (Interquartile Range) method was used to handle extreme values


## 6. Feature Engineering

### Encoding

#### One Hot Encoding
Used for categorical input features.

#### Label Encoding
Used for the target column.

- Good → 1
- Bad → 0


### Feature Scaling

#### StandardScaler
Feature scaling was applied to standardize numerical features.

## 7. Train-Test Split

The dataset was divided into:

- 80% Training Data
- 20% Testing Data


## 8. Model Building

The following Machine Learning models were trained and evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree Classifier
- Random Forest Classifier
- AdaBoost Classifier
- Gradient Boosting Classifier
- K-Nearest Neighbors (KNN)
- XGBoost Classifier

## 9. Model Evaluation

Models were evaluated using the following metrics:

- Accuracy Score
- Confusion Matrix
- Precision Score
- Recall Score
- F1 Score


## 10. Best Model Selection

The best model was selected based on overall evaluation metrics.

### Best Performing Model
- Gradient Boosting Classifier


## 11. Prediction System

The model predicts whether a customer belongs to:

- Good Risk
- Bad Risk

### Prediction Workflow
1. Input data preprocessing
2. Encoding
3. Feature scaling
4. Model prediction



## 12. Results

The project successfully predicts customer credit risk using Machine Learning techniques.


# Author

Darsana Shabu
