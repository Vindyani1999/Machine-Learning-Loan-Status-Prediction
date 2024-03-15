# Loan Status Prediction
Machine Learning Project

[![-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](https://github.com/BaseMax?tab=repositories)

This project aims to predict loan status based on various features using machine learning techniques. Loan status prediction is a crucial task in financial institutions to assess the risk associated with granting loans to individuals or businesses. By analyzing historical data, this application predicts whether a loan applicant will fully pay off the loan or default.

[![-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](https://github.com/BaseMax?tab=repositories)


## Table of Contents

- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Technologies Used](#technologies-used)

---

## Data Preprocessing

The data preprocessing phase involves handling missing values, dropping irrelevant columns, and encoding categorical variables. Key steps include:

- Dropping unnecessary columns ('Loan ID', 'Customer ID', 'Maximum Open Credit', 'Number of Open Accounts', 'Months since last delinquent', 'Years in current job').
- Handling missing values in 'Credit Score' and 'Annual Income' columns.
- Encoding categorical variables using one-hot encoding.

---

## Exploratory Data Analysis

Exploratory data analysis (EDA) provides insights into the relationships between different features and the target variable. Key explorations include:

- Visualizing the distribution of loan status.
- Correlation analysis to identify least contributing features.
- Scatter plots to visualize the relationship between features and loan status.

---

## Model Building

Two machine learning models are built for loan status prediction:

### Logistic Regression

- Training a logistic regression model.
- Feature scaling using StandardScaler.
- Grid search for hyperparameter tuning.

### Support Vector Machine (SVM)

- Training an SVM model.
- Feature scaling using StandardScaler.
- Grid search for hyperparameter tuning.

---

## Model Evaluation

Model evaluation is performed using various metrics including accuracy, confusion matrix, ROC curve, precision-recall curve, and learning curves. Key evaluations include:

- Cross-validation to assess model performance.
- Confusion matrix visualization.
- ROC curve and AUC score.
- Precision-recall curve.

---

## Technologies Used

- *Python*
- *Libraries:* NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
