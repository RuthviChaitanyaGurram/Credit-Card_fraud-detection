Credit Card Fraud Detection
This report presents the performance of various machine learning models for credit card fraud detection. The models were trained and evaluated on a dataset containing credit card transactions, where the target variable was a binary indicator of fraud (0 for non-fraudulent and 1 for fraudulent transactions).

Dataset
The dataset contained 4,681 instances, with the following class distribution:

Non-fraudulent transactions (0): 4,669
Fraudulent transactions (1): 12
Models and Performance
The following machine learning models were evaluated:

1. Logistic Regression
Accuracy: 0.9974
Precision: 1.00 (non-fraudulent), 0.00 (fraudulent)
Recall: 1.00 (non-fraudulent), 0.00 (fraudulent)
F1-score: 1.00 (non-fraudulent), 0.00 (fraudulent)
2. Random Forest
Accuracy: 0.9989
Precision: 1.00 (non-fraudulent), 0.89 (fraudulent)
Recall: 1.00 (non-fraudulent), 0.67 (fraudulent)
F1-score: 1.00 (non-fraudulent), 0.76 (fraudulent)
3. Gradient Boosting
Accuracy: 0.9977
Precision: 1.00 (non-fraudulent), 0.56 (fraudulent)
Recall: 1.00 (non-fraudulent), 0.42 (fraudulent)
F1-score: 1.00 (non-fraudulent), 0.48 (fraudulent)
4. Support Vector Machine (SVM)
Accuracy: 0.9974
Precision: 1.00 (non-fraudulent), 0.00 (fraudulent)
Recall: 1.00 (non-fraudulent), 0.00 (fraudulent)
F1-score: 1.00 (non-fraudulent), 0.00 (fraudulent)
5. K-Nearest Neighbors (KNN)
Accuracy: 0.9972
Precision: 1.00 (non-fraudulent), 0.33 (fraudulent)
Recall: 1.00 (non-fraudulent), 0.08 (fraudulent)
F1-score: 1.00 (non-fraudulent), 0.13 (fraudulent)
Observations
All models performed exceptionally well in detecting non-fraudulent transactions, with perfect precision and recall scores.
However, the performance in detecting fraudulent transactions varied across models.
The Random Forest model exhibited the highest overall performance, with an accuracy of 0.9989 and a relatively high F1-score of 0.76 for fraudulent transactions.
The Gradient Boosting model also showed promising results, with an accuracy of 0.9977 and an F1-score of 0.48 for fraudulent transactions.
Logistic Regression, SVM, and KNN models struggled to detect fraudulent transactions, with F1-scores of 0.00, 0.00, and 0.13, respectively.
Recommendations
Based on the results, the Random Forest model is recommended for credit card fraud detection due to its high overall accuracy and relatively good performance in detecting fraudulent transactions. However, it is important to note that the dataset exhibited a significant class imbalance, with a much smaller number of fraudulent instances compared to non-fraudulent instances. Techniques such as oversampling or undersampling may be explored to improve the performance of the models in detecting fraudulent transactions.
