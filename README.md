# Credit-Card-Fraud-Detection-Using-Machine-Learning

The main concern of this research was to detect least and accurate false fraud detection. Credit card fraud is lack of security. Credit Card Fraud can be used for applications as paying with credit card make it easier to avoid loses from fraud. This project has examined the performance of five kinds of classification models namely Random Forest Algorithm, Decision Tree Algorithm, Naïve Bayes, KNN Algorithm, SVM Algorithm. A real-life dataset on credit card transactions is used in our experiment. Among all the methods, the SVM one has the maximum accuracy.

Although SVM obtains good results on small set data, there are still some problems such as imbalanced data. Our future work will focus on solving these problems. For example, the voting mechanism assumes that each of base classifiers has equal weight, but some of them may be more important than others. Therefore, we also try to make some improvement for this
algorithm.

The results indicate the optimal accuracy for SVM, Naïve Bayes, KNN, Random Forest Classification and Decision Tree Classification are 91.87%, 90.24%, 89.83%, 91.05% and 88.62% respectively.

ABOUT THE DATASET-

The dataset for this project is taken from the kaggle.
https://www.kaggle.com/mlg-ulb/creditcardfraud

The datasets contain transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependent cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.


