# Gender-Recognition-Using-Voice
Finding the best Machine learning model to predict the gender using the acoustic properties, by taking the dataset from kaggle which consists of 3168 recorded samples of voice.

I took dataset from kaggle which consisted of 3168 recorded samples of male and female speakers.

Trained the model on 7 different classifiers by keeping training dataset size = 80% and testing dataset size = 20%

For all the 7 classifiers, I did hyperparameter tuning using gridsearchcv to find the best parameters and did the Recursive Feature Elimination.

Decision Tree
----------------------------------------------------

Accuracy score :0.9511041009463722
Precision score :0.9543973941368078
Recall score :0.9451612903225807
F1 score :0.9497568881685575


Random Forest
----------------------------------------------------

Accuracy score :0.9747634069400631
Precision score :0.9803921568627451
Recall score :0.967741935483871
F1 score :0.9740259740259739

Gradient Boosting
----------------------------------------------------

Accuracy score :0.9700315457413249
Precision score :0.9739413680781759
Recall score :0.964516129032258
F1 score :0.9692058346839546

K Nearest Neighbours
----------------------------------------------------

Accuracy score :0.9810725552050473
Precision score :0.9821958456973294
Recall score :0.9821958456973294
F1 score :0.9821958456973294

Support Vector Machine
----------------------------------------------------

Accuracy score :0.9826498422712934
Precision score :0.9880239520958084
Recall score :0.9792284866468842
F1 score :0.9836065573770492


Logistic Regression
----------------------------------------------------

Accuracy Score   : 0.9810725552050473

Ensemble  
----------------------------------------------------

In this model,we predicted the output using 3 different base models SVM,KNN and Logistic regression.

Accuracy score :0.9873817034700315
Precision score :0.991044776119403
Recall score :0.9851632047477745
F1 score :0.9880952380952381
