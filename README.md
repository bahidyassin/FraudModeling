# Overview
This project aims to build a model to detect fraudulent transactions based on historical data. We utilize two interpretable machine learning algorithms: Logistic Regression and Decision Tree, to predict fraud cases effectively and understand the model behavior.

### File Structure:
$ tree
.
├── Fraud Model Overview.pdfL: Details the models used and the results.
|
├── Fraud Modeling.ipynb: Code needed to run the models.
|
├── Model Deployment Strategy.pdf: Details relevant MLOPs proceedures to deploy the model to an AWS instance.
|
├── Requirements.txt : needed libraries for the model to run.
|
└── README.md




## Dataset
The dataset used for this project can be found on Kaggle: Fraudulent Transactions Data. The dataset contains transactional information, such as transaction type, amount, origin and destination account balances, and labels indicating fraudulent transactions.

## Models
Logistic Regression: A linear model that predicts the probability of a transaction being fraudulent. It is simple to interpret and useful for understanding the impact of each feature on the prediction.

Decision Tree: A non-linear model that creates a tree-like structure to make decisions based on the features. It is more flexible than logistic regression and can capture complex interactions between features.
