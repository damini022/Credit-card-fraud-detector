# Credit Card Fraud Detection
This project detects fraudulent credit card transactions using Machine Learning (Logistic Regression). It uses anonymized and imbalanced transaction data to train and evaluate a classification model.

# Problem Statement
Credit card fraud detection is crucial for financial institutions. The challenge lies in accurately identifying fraudulent transactions (which are rare) without mislabeling genuine ones. This project aims to:

- Classify transactions as Fraudulent (1)or Genuine (0)
- Worked on an imbalanced dataset using under-sampling and evaluated model performance primarily using accuracy and confusion matrix.
- Maximize recallto catch most fraudulent cases


#Dataset
- Dataset: [Credit Card Fraud Detection - Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Rows: 284,807 transactions
- Features: 30 numerical (anonymized), including `Time`, `Amount`, and `Class` (target)



# Tech Stack

- Python
- NumPy, Pandas
- Scikit-learn (Logistic Regression, train-test split, accuracy_score)
- Jupyter Notebook / Google Colab



# Approach

1. Data Preprocessing
   - Loaded the dataset
   - Checked for null values
   - Worked on an imbalanced dataset and focused evaluation beyond accuracy.

2. Exploratory Data Analysis
   - Count of fraud vs genuine
   - Transaction amount analysis

3. Model Building
   - Logistic Regression
   - Train-test split (80/20)

4. Evaluation
   - Accuracy score
   - Confusion matrix
   - Emphasis on recall(for catching frauds)

---


## Model Performance
- Training Accuracy: ~94%
- Test Accuracy: ~94%
- Note: Accuracy is reported on an under-sampled balanced dataset.



