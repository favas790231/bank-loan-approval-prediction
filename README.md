# Bank Loan Approval Prediction

A Machine Learning classification project that explores a bank loan dataset and predicts whether a loan application will be approved or rejected. This project focuses on Exploratory Data Analysis (EDA), data preprocessing, classification algorithms, and model evaluation.

## Project Overview

The objective of this project is to analyze the factors associated with loan approval and build classification models to predict loan approval outcomes.

The project includes data cleaning, exploratory data analysis, visualization, model training, and performance comparison using multiple classification algorithms.

## Dataset Information

- **Dataset Size:** 900 rows
- **Features:** 14 columns (including target and additional columns)
- **Target Variable:** `loan_approved`
- **Target Classes:**
  - `0` – Rejected
  - `1` – Approved

## Exploratory Data Analysis

The following visualizations were created to understand the dataset and identify patterns.

### 1. Loan Approval Distribution



### 2. Credit History Analysis



### 3. Education and Property Area Analysis



## Data Preprocessing

The following preprocessing steps were performed:

- Checked and handled missing values.
- Removed duplicate records.
- Converted categorical features into numerical representations.
- Prepared features and target variables.
- Split the dataset into training and testing sets.
- Applied feature scaling where required.

## Machine Learning Models

Implemented and compared the following 10 classification models:

1. Logistic Regression
2. K-Nearest Neighbors (KNN) – k=5
3. K-Nearest Neighbors (KNN) – k=7
4. Support Vector Machine (SVM)
5. Gaussian Naive Bayes
6. Decision Tree
7. Random Forest
8. Gradient Boosting
9. AdaBoost
10. XGBoost

## Model Evaluation

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

### Logistic Regression – Confusion Matrix



### Model Accuracy Comparison



## Key Observations

- The dataset contains more approved applications than rejected applications.
- Credit history shows a strong relationship with loan approval.
- Applicant income and loan amount show a strong correlation.
- Multiple classification algorithms achieved similar accuracy scores.
- Confusion matrices and classification reports were used to compare model performance beyond accuracy alone.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Project Structure

```text
bank-loan-approval-prediction/
│
├── images/
│   ├── loan-approval-distribution.png
│   ├── credit-history-analysis.png
│   ├── education-property-analysis.png
│   ├── logistic-regression-confusion-matrix.png
│   └── model-accuracy-comparison.png
│
├── loan_approval_eda_and_classification.ipynb
│
└── README.md
```

## Conclusion

This project provided practical experience in Exploratory Data Analysis, data preprocessing, and implementing multiple classification algorithms. Ten classification models were trained and compared using different evaluation metrics to understand their performance.

The project also highlights the importance of evaluating both approved and rejected applications rather than relying only on overall accuracy.

Overall, this project strengthened my understanding of the Machine Learning workflow, from data exploration and preprocessing to model training and evaluation.
