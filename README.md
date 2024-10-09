## Credit Card Fraud Detection using Logistic Regression

### Project Overview

This project focuses on detecting fraudulent credit card transactions using a **Logistic Regression** model. The dataset used is publicly available on Kaggle, containing anonymized transaction details, including whether a transaction is legitimate or fraudulent. The goal is to train a machine learning model capable of identifying fraudulent transactions based on patterns in the data.

### Requirements

- Python 3.x
- Libraries: `numpy`, `pandas`, `scikit-learn`, `os`
- Dataset: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download)

Make sure to place the `creditcard.csv` file in the same folder as your project.

### Project Steps

1. **Data Loading**: The dataset is loaded and the basic structure is analyzed, including the distribution of legitimate and fraudulent transactions.
   
2. **Data Preprocessing**: To handle the class imbalance between legitimate and fraudulent transactions, a balanced subset of the data is created.

3. **Model Selection**: A **Logistic Regression** model is selected for this binary classification problem.

4. **Training and Testing**: The dataset is split into training and test sets. The model is trained using the training data, and its performance is evaluated on both the training and test sets.

5. **Evaluation**: Accuracy is calculated to assess the model's performance on detecting fraudulent transactions.

### Results

- **Training Accuracy**: 96.06%
- **Test Accuracy**: 94.41%

### Conclusion

The Logistic Regression model achieves a high level of accuracy in identifying fraudulent credit card transactions. However, further evaluation using additional metrics like **precision** and **recall** would provide a more comprehensive understanding of the model's performance, particularly given the imbalance in the dataset.
