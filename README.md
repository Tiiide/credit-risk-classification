# credit-risk-classification
Homework for Module 20- Supervised Learning


For this project, we are analyzing a dataset of historical lending activity to build a predictive model for identifying creditworthiness of borrowers based on the loans in our dataset being classified as either high-risk or healthy.

Our dataset includes Loan Size, Interest Rate, Borrower Income, Debt to Income, Number of Accounts, Derrogatory Marks, Total Debt, and Loan Status. With Loan Status being our target value that we want to train our model to predict, the remaining values are being used as our features.

Loan Status itself is a skewed metric, with a ratio of 75036 : 2500 for the two values used in that set. We elected to use a Logistic Regression model for its ability to handle binary classification problems.

Results
* Accuracy - Our score of 0.99 indicates that our model correctly predicts the loan status in 0.99 of cases
* Precision Score on High Risk Loans - With a score of 0.84, we can determine that our model will misclassify a small percentage of healthy loans as high-risk.
* Recall Score on High Risk Loans - At 0.94, this score shows that our model correctly identifies 94% of "high-risk" loans that are actually high-risk.
* Precision and Recall on Healthy Loans - Our model shows 1.00 and 0.99 respectively for precision and recall on our healthy loans which shows a near perfect ability to predict these loan types.


With the classification report showing near perfect scores for predicting healthy loans and a high predictive value for high-risk loans, the Logistic Regression model fares well with the classification problem. Although it may misclassify some healthy loans as high-risk, it shows that it correctly identifies nearly all high-risk loans. This should provide valuable predictive insight for classifying borrowers' creditworthiness.