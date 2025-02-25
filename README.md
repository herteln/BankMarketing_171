# BankMarketing_171
Practical Application Assignment 17.1: Comparing Classifiers


Test Split:
To perform the assignment experiment with different classification model using two options of test split: 80/20 and 70/30.
 
List of Classifiers that were tried:
KNN Classifer
Logistic Regression
SVC
DecisionTree Classifer
Random Forest Classifier


Best Model:
Logistic Regression : 91
Random Forest Classifier : 91


Best Hyper Parameters and Training Score:
Fitting 5 folds for each of 6 candidates, totalling 30 fits
Best parameters for LogisticRegression: {'classifier__C': 10.0, 'classifier__max_iter': 3000, 'classifier__solver': 'liblinear'}
Best cross-validation score for LogisticRegression: 0.90
Fitting 5 folds for each of 6 candidates, totalling 30 fits
Best parameters for RandomForest: {'classifier__max_depth': 20, 'classifier__n_estimators': 100}
Best cross-validation score for RandomForest: 0.90
Fitting 5 folds for each of 12 candidates, totalling 60 fits
Best parameters for DecisionTree: {'classifier__max_depth': 5, 'classifier__min_samples_split': 5}
Best cross-validation score for DecisionTree: 0.90
Fitting 5 folds for each of 6 candidates, totalling 30 fits
Best parameters for SVC: {'classifier__C': 10.0, 'classifier__gamma': 'scale'}
Best cross-validation score for SVC: 0.90
Fitting 5 folds for each of 8 candidates, totalling 40 fits
Best parameters for KNN: {'classifier__n_neighbors': 9, 'classifier__weights': 'distance'}
Best cross-validation score for KNN: 0.89


Best Test Score:
Accuracy of best LogisticRegression on test set: 0.91
Accuracy of best RandomForest on test set: 0.91
Accuracy of best DecisionTree on test set: 0.90
Accuracy of best SVC on test set: 0.90
Accuracy of best KNN on test set: 0.91


Top Features:
Age
Duration
Plays
Outcome
