# Give-Me-Some-Credit
Machine Learning Models to predict default
# Overview
With this code is analysed a dataset related to the provision of credit to borrowes. It records whether a certain person experienced 90 days past due delinquency or worse, and a set of variables (predictors) related to each person.

The aim of the analysis is to test the capability of a set of models such as Linear regression (LR), Support Vector Machine (SVM), and Decision Tree (Tree) to predict the default of a borrower (measured with the variable "Person experienced 90 days past due delinquency or worse").

To this aim, first is implemented a linear regression model that elaborate the whole feature dataset, then the 2 most relevant features are selected, and the rest of the analysis is developed based on these 2 features. Each model (LR, SVM, Tree) is then newly built different times varying the hyperparametes: C for LR and SVM, Max Depth for Tree), and its accuracy computed for both the train dataset and the test dataset.

The models with the best set of hyperparameters and parameters are finally selected and plotted in a chart.


Selected features:
- Age
- NumberOfTime30-59DaysPastDueNotWorse

Logistic Regression Model, C=100
- Training accuracy: 0.9333266666666666
- Test accuracy: 0.9836359516467493

Support Vector Machine Model, Kernel rbf, gamma=0.50, C=5.0
- Training accuracy: 0.9335133333333333
- Test accuracy: 0.9844044018403397

Decision Tree Model, criterion gini, max_depth 6
- Training accuracy: 0.93356
- Training accuracy: 0.9839512132646325
