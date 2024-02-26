Context about the data

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

Content

The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

About the columns of data 
Time contain Number of seconds elapsed between this transaction and the first transaction in the dataset

Features V1, V2, … V28 are the principal components obtained with PCA

This is a heatmap. 
It is a graphical representation of data where the values are represented as colors. The color gradient is typically from blue to red, with blue representing low values and red representing high values.

![download](https://github.com/Vedu36/Credit-Card-Fraud-Detection-Using-Logistics-Regression/assets/118358451/cf6b4c66-a86a-438d-9076-962cb6446776)


My Confusion Matrix 

The graph you are referring to is called a confusion matrix. A confusion matrix is a table that is used to evaluate the performance of a classification model. It compares the actual target values with the predicted target values.

![download (1)](https://github.com/Vedu36/Credit-Card-Fraud-Detection-Using-Logistics-Regression/assets/118358451/dc67892e-5235-4086-b0da-caad5322f040)
