# Gender-Recognition-Using-Voice
Finding the best Machine learning model to predict the gender using the acoustic properties, by taking the dataset from kaggle which consists of 3168 recorded samples of voice.

I took dataset from kaggle which consisted of 3168 recorded samples of male and female speakers.

Trained the model on 7 different classifiers by keeping training dataset size = 80% and testing dataset size = 20%

For all the 7 classifiers, I did hyperparameter tuning using gridsearchcv to find the best parameters and did the Recursive Feature Elimination.

Decision Tree
----------------------------------------------------

Decision Tree Accuracy Score:  0.9511041009463722

Classification Report

  precision    recall  f1-score   support

           0       0.95      0.96      0.95       324
           1       0.95      0.95      0.95       310

    accuracy                           0.95       634
   macro avg       0.95      0.95      0.95       634
weighted avg       0.95      0.95      0.95       634


Random Forest
----------------------------------------------------

Random Forest Accuracy Score:  0.9747634069400631

Classification Report

precision    recall  f1-score   support

           0       0.97      0.98      0.98       324
           1       0.98      0.97      0.97       310

    accuracy                           0.97       634
   macro avg       0.97      0.97      0.97       634
weighted avg       0.97      0.97      0.97       634


Gradient Boosting
----------------------------------------------------

Gradient Boosting Accuracy Score: 0.97003

Classification Report


 precision    recall  f1-score   support

        male     0.9664    0.9753    0.9708       324
      female     0.9739    0.9645    0.9692       310

    accuracy                         0.9700       634
   macro avg     0.9702    0.9699    0.9700       634
weighted avg     0.9701    0.9700    0.9700       634


K Nearest Neighbours
----------------------------------------------------

K Nearest Neighbours Accuracy Score: 0.9810725552050473

Classification Report

precision    recall  f1-score   support

        male     0.9798    0.9798    0.9798       297
      female     0.9822    0.9822    0.9822       337

    accuracy                         0.9811       634
   macro avg     0.9810    0.9810    0.9810       634
weighted avg     0.9811    0.9811    0.9811       634


Support Vector Machine
----------------------------------------------------

Support Vector Machine Accuracy Score   :   0.9826498422712934

Classification Report

precision    recall  f1-score   support

        male     0.9767    0.9865    0.9816       297
      female     0.9880    0.9792    0.9836       337

    accuracy                         0.9826       634
   macro avg     0.9823    0.9829    0.9826       634
weighted avg     0.9827    0.9826    0.9827       634


Logistic Regression
----------------------------------------------------

Logistic Regression Accuracy Score   :    0.9810725552050473

Classification Report

precision    recall  f1-score   support

      female       0.98      0.98      0.98       297
        male       0.99      0.98      0.98       337

    accuracy                           0.98       634
   macro avg       0.98      0.98      0.98       634
weighted avg       0.98      0.98      0.98       634

Ensemble  
----------------------------------------------------

In this model,we predicted the output using 3 different base models SVM,KNN and Logistic regression.

Ensemble Accuracy Score:    0.9873817034700315
