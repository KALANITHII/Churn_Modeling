# Churn Prediction Using Machine Learning

## Overview
This project aims to predict customer churn, a critical concern for businesses. Customer churn occurs when customers stop doing business with a company. Predicting churn can help companies take proactive measures to retain at-risk customers. In this project, we use Machine Learning models, including Logistic Regression and Support Vector Machine (SVM), while addressing class imbalance using the Synthetic Minority Over-sampling Technique (SMOTE).

## Data
- We use a dataset containing customer information, including demographics, usage patterns, and historical data.
- The target variable is "Churn," which indicates whether a customer has churned or not.
- The dataset consists of 10,000 records with 20 features.

## Data Preprocessing
- We handle missing values by imputation and encode categorical variables.
- Feature scaling is applied to ensure uniformity.
- Data cleaning is performed to improve model performance.

## Exploratory Data Analysis (EDA)
- EDA reveals interesting insights, such as a correlation between customer tenure and churn.
- Visualizations illustrate patterns and trends in the data.

## Handling Class Imbalance
- Class imbalance is addressed using the Synthetic Minority Over-sampling Technique (SMOTE).
- SMOTE generates synthetic samples to balance the dataset.
- Visualizations demonstrate class distribution before and after SMOTE.

## Model Selection
- We choose Logistic Regression and SVM for churn prediction.
- Logistic Regression provides simplicity and interpretability, while SVM can capture complex patterns.
- Both models have proven effective in churn prediction scenarios.

## Model Training
- The selected models are trained using the preprocessed data.
- Code examples are provided in Jupyter notebooks for clarity.
- Hyperparameter tuning is performed to optimize model performance.

## Model Evaluation
- Model evaluation metrics include accuracy, precision, recall, F1-score, and ROC-AUC.
- Results show the strengths and weaknesses of each model.
- The choice of evaluation metrics is essential for effective churn prediction.

## Results
- The project's results reveal the effectiveness of Logistic Regression and SVM in predicting churn.
- Insights gained from the models can guide businesses in reducing customer churn.
- Areas for improvement and future work are discussed.

## Acknowledgments
- We acknowledge the dataset source and libraries used, including scikit-learn and SMOTE implementation.


## Contact
- For inquiries or collaboration opportunities, contact [thananseyakalanithi@gmail.com].
