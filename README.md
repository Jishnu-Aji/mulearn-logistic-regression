# Logistic Regression – Bank Churn Prediction

This project was completed as part of the **μLearn AI Logistic Regression** task.

## About the Project

The objective of this project is to build a **Logistic Regression machine learning model** to predict whether a bank customer will churn based on customer-related features.

## Dataset

The dataset used is `bank_churn.csv`.

### Features

- `balance`
- `credit_card`
- `credit_score`
- `estimated_salary`
- `gender`
- `products_number`

### Target

- `churn` – Indicates whether the customer churned.

The `ID` column was excluded from model training because it is only a customer identifier.

## Methodology

The following steps were performed:

1. Imported the required Python libraries.
2. Loaded the bank churn dataset.
3. Explored the dataset and its features.
4. Checked for missing values.
5. Analyzed the churn distribution.
6. Separated the features and target variable.
7. Split the dataset into training and testing sets.
8. Trained a Logistic Regression model.
9. Generated predictions on the test data.
10. Evaluated the model using:
    - Accuracy
    - Precision
    - Recall
    - F1-score
    - Confusion Matrix
11. Analyzed Logistic Regression feature coefficients.
12. Visualized the model coefficients.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Repository Contents

```text
mulearn-logistic-regression/
│
├── Logistic_Regression.ipynb
├── course-completion.png
└── README.md
