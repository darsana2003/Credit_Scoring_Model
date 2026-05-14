# Credit_Scoring_Model
This project focuses on predicting the credit risk of loan applicants using Machine Learning classification algorithms. The model analyzes customer financial and personal information to determine whether the applicant has a **Good** or **Bad** credit risk.

## Dataset Information
- Dataset Name : German Credit Dataset
- Target Column : Risk

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

### 1. Data Collection
The dataset was collected from Kaggle and loaded using Pandas.

#### Dataset Features
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

### 2. Data Exploration
Initial exploration was performed to understand the dataset structure.

### Steps Performed
- Checked dataset shape
- Viewed column names
- Identified missing values
- Checked duplicate values
- Generated statistical summary

### 3.Exploratory Data Analysis (EDA)
EDA was performed to understand patterns, relationships, and customer behavior.

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
  
#### 4.Data Cleaning
- Missing Value Handling
- Removed unnecessary columns
- Checked inconsistent values
- Removed extra spaces

#### 5. Outlier Detection and Removal
Outliers were detected using Boxplots.
The IQR (Interquartile Range) method was used to handle extreme values.

#### 6. Feature Engineering
### Encoding
## One Hot Encoding
Used for input categorical columns.
## Label Encoding
Used for target column.
- Good → 1
- Bad → 0
### Scaling
## StandardScaler

#### 7.Train Test Split
The dataset was divided into:
- 80% Training Data
- 20% Testing Data

#### 10. Model Building
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree Classifier
- Random Forest Classifier
- AdaBoostClassifier
- Gradient Boosting Classifier
- KNeighborsClassifier
- XGBClassifier

#### 11. Model Evaluation
- Accuracy Score
- Confusion Matrix
- Precision Score
- Recall Score
- F1 Score

#### 12. Best Model Selection
The best model was selected based on overall performance metrics.
## Best Performing Model
- Gradient Boosting Classifier
#### 13. Prediction System
A prediction system was created to classify customers as:
- Good Risk
- Bad Risk

##### Prediction Steps
1. Input data preprocessing
2. Encoding
3. Feature scaling
4. Model prediction

#### Results
The project successfully predicts customer credit risk using Machine Learning techniques.
