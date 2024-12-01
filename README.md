# Credit-Card-Fraud-Detection


## Description
This project implements a machine learning model to detect fraudulent transactions in credit card data. The goal is to identify potentially fraudulent transactions to minimize losses and enhance security for financial institutions and consumers.

## Data
Data
The dataset used in this project is derived from real-world credit card transactions. It contains features such as:
- Transaction Amount: The amount of money involved in the transaction.
- Time: The time elapsed since the first transaction in seconds.
- V1-V28: Anonymized features resulting from PCA (Principal Component Analysis) to protect user identities.
- Class: A binary variable indicating whether a transaction is fraudulent (1) or legitimate (0).

  The dataset is imbalanced, with a significantly higher number of legitimate transactions compared to fraudulent ones.

  ## Model
  This project utilizes various machine learning algorithms, including:
 - Logistic Regression
 -  Decision Trees
 - Random Forests
   
   The models are evaluated using metrics such as accuracy, precision, recall, and F1-score to ensure effective fraud detection.

   ## Results
   The results section of the notebook provides detailed insights into model performance. Key metrics include:
- Accuracy: The proportion of true results among the total number of cases examined.
- Precision: The ratio of correctly predicted positive observations to the total predicted positives.
- Recall: The ability of the model to find all relevant cases (fraudulent transactions).
- F1 Score: The weighted average of precision and recall.
  Visualizations such as confusion matrices and ROC curves are also included to illustrate model performance.


  Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.
