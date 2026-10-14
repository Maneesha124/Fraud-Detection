
# Credit Card Fraud Detection Using Snowflake and XGBoost

## Project Overview
This project detects potentially fraudulent credit card transactions using
machine learning. Snowflake is used for data storage and processing, while
Python and XGBoost are used to train and evaluate the classification model.

## Technologies Used
- Snowflake
- Python
- Snowpark ML
- XGBoost
- SQL
- Pandas
- Scikit-learn

## Project Workflow
1. Load credit card transaction data into Snowflake.
2. Prepare the dataset and select features.
3. Split the data into training and testing sets.
4. Train an XGBoost classification model.
5. Evaluate the model using classification metrics.
6. Register the model in Snowflake Model Registry.
7. Process incoming transactions and store predictions.

## Model Evaluation

| Metric | Score |
|---|---:|
| Accuracy | 99.94% |
| Precision | 87.06% |
| Recall | 74.75% |
| F1-score | 80.43% |
| ROC-AUC | 97.49% |

These metrics were obtained during model evaluation on the test set.

## Current Pipeline Results
- Transactions in the prediction table: 6
- Transactions classified as fraud: 0
- Average predicted fraud probability: 0.000004

These are the current results for the six processed transactions,
not a measure of overall model performance.

## Project Files
The Python notebook and SQL scripts will be added to this repository.

## Disclaimer
This project is for educational purposes. Model predictions should
not be treated as definitive proof of fraud.
