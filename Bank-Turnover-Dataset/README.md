# Bank-Turnover-Dataset
Customers began to leave the Bank every month. A little, but noticeable. Bank marketers decided that it was cheaper to retain existing customers than to attract new ones. We need to predict whether the client will leave the bank in the near future or not. We are provided with historical data on customer behavior and termination of agreements with the bank.

Our goal is to build a model with extremely large measure F1. For a successful solution, we need to bring the metric to 0.59.

Additionally, we will measure the AUC-ROC, compare its value with the F1 indicator.

Data source: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

### Signs
- RowNumber - row index in data
- CustomerId - unique customer identifier
- Surname - surname
- CreditScore - credit rating
- Geography - country of residence
- Gender
- Age
- Tenure - how many years a person has been a bank client
- Balance - account balance
- NumOfProducts - the number of bank products used by the client
- HasCrCard - the presence of a credit card
- IsActiveMember - client activity
- EstimatedSalary - estimated salary

## Libraries used:
Pandas , NumPy, Scikit-learn, Matplotlib, Seaborn
