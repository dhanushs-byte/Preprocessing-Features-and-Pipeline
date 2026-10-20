# Preprocessing-Features-and-Pipeline

## Objective
Build a machine learning pipeline to predict loan default.

## Dataset
Synthetic loan-default dataset containing numeric
and categorical features.

## Preprocessing
- SimpleImputer: median for numeric columns
- SimpleImputer: most frequent for categorical columns
- KNNImputer experiment
- StandardScaler for numeric features
- OneHotEncoder for nominal categories
- OrdinalEncoder for ordered categories

## Feature Engineering
- Application year and month
- Income-to-loan ratio
- Log transformation of loan amount

## Model
Logistic Regression inside a Pipeline
with a ColumnTransformer.

## Evaluation
Pipeline CV accuracy: [your actual score]

## Predictions
Predictions for three new rows: [your actual output]

## Model Saving
Saved and loaded using joblib.
