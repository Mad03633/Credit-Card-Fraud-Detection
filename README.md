# Credit Card Fraud Detection

This project is focused on detecting fraudulent credit card transactions using a dataset of transactions made by European cardholders over a period of two days in September 2013. The dataset contains 492 frauds out of 284,807 transactions, which is highly imbalanced.

## Dataset

The dataset can be downloaded from Kaggle: [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud).

### File

- `creditcard.csv`: Contains the transaction data.

### Features

- **Time**: Number of seconds elapsed between this transaction and the first transaction in the dataset.
- **V1 - V28**: The result of a PCA transformation. Due to confidentiality issues, the original features are not provided.
- **Amount**: Transaction amount.
- **Class**: The response variable (1 for fraud, 0 for valid transactions).

## Conclusion

The Random Forest Classifier has been used to detect fraudulent transactions. The performance metrics and confusion matrix have been displayed to evaluate the model's effectiveness.

## Dependencies

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn