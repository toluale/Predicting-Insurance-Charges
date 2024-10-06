# Predicting-Insurance-Charges
This project combines predictive analytics with feature engineering in the healthcare/insurance domain.

The task is to predict healthcare cost of customers for a Health Insurance Company.

The variable 'charges' is the target variable.

## insurance.csv
| Column    | Data Type | Description                                                      |
|-----------|-----------|------------------------------------------------------------------|
| `age`       | int       | Age of the primary beneficiary.                                  |
| `sex`       | object    | Gender of the insurance contractor (male or female).             |
| `bmi`       | float     | Body mass index, a key indicator of body fat based on height and weight. |
| `children`  | int       | Number of dependents covered by the insurance plan.              |
| `smoker`    | object    | Indicates whether the beneficiary smokes (yes or no).            |
| `region`    | object    | The beneficiary's residential area in the US, divided into four regions. |
| `charges`   | float     | Individual medical costs billed by health insurance.             |


The dataset requires some data cleaning and feature engineering to get a top predictive model.
I develop a regression model using XGBoost to predict insurance charges for customers of different demographic. 
The process involves exploratory data analysis, data cleaning techniques and feature engineering.
The XGBoost model was trained using a 5-fold cross validation and the output was evaluated using R-Squared.
I calculated the models feature importance and identified that the engineered features contributed signifficantly to the model's performance.

