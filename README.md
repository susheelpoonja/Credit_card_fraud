`Fraud Detection - Credit Card Fraud Detection`

# 
This datasets have 492 frauds out of 284,807 transactions. It is highly unbalanced, the positive class--1 (frauds) account for 0.172% of all transactions.

Feature `Time` contains the seconds elapsed between each transaction and the first transaction in the dataset.But, we did not consider `Time` for training purpose as it is of no use to build the models and may not impact our target variable.

The feature `Amount` is the transaction Amount, this feature is scaled using StandardScaler.

Feature `Class` is the response variable

This project mainly focuses on handling imbalanced datasets and detecting credit-card frauds. I have used to following models to look for the best model.

    a) Logistic Regression

    b) RandomForestClassifier

    c) DecisionTreeClassifier

    d) XGBCLassifier

    e) KNeighbors Classifier

These models are fittted to different datasets acquired after Oversampling using SMOTE and Undersampling techniques.

# AFTER ALL ANALYSIS, THE BEST MODEL FOR THE FOLLOWING DATASET IS RANDOM FOREST MODEL WITH OVERSAMPLED DATA USING SMOTE
