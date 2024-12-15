# Attributes Affect Car Insurance Waive using SAS

## Project Overview
This project focuses on predicting customer churn - a critical metric for many businesses, especially in the banking and telecom sectors. We use an XGBoost classifier, a powerful machine learning algorithm, to predict the likelihood of customers leaving a company.

## Data Description
The dataset used in this project contains various customer attributes, such as age, balance, and number of products used, along with a target variable indicating whether the customer has exited (churned) or not.

## Repository Contents
- `train.csv`: Training dataset containing customer attributes and the target variable.
- `car_insurance_prediction.ipynb: Jupyter notebook with the analysis and model training.
- submission.csv: Predictions for the test dataset.
- README.md: Documentation of the project.

## Key Steps
1. **Data Preprocessing**: Cleaning and encoding of the data, making it suitable for model training.
2. **Exploratory Data Analysis (EDA)**: Analyzing the data to understand patterns and relationships.
3. **Feature Engineering**: Selecting and transforming features for model training.
4. **Model Training**: Building and training an XGBoost classifier.
5. **Model Evaluation**: Evaluating the model's performance using accuracy and other metrics.
6. **Feature Importance Analysis**: Understanding which features are most impactful in predicting churn.
7. **Predictions**: Generating churn predictions on the test dataset.

## Technologies Used
- Python
- Pandas
- Matplotlib and Seaborn for visualizations
- Scikit-learn for data preprocessing and model evaluation
- XGBoost for the prediction model
