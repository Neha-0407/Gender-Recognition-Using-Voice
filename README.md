# Gender-Recognition-Using-Voice
Finding the best Machine learning model to predict the gender using the acoustic properties, by taking the dataset from kaggle which consists of 3168 recorded samples of voice.

I took dataset from kaggle which consisted of 3168 recorded samples of male and female speakers.

Trained the model on 7 different classifiers by keeping training dataset size = 80% and testing dataset size = 20%

For all the 7 classifiers, I did hyperparameter tuning using gridsearchcv to find the best parameters and did the Recursive Feature Elimination.

Decision Tree
----------------------------------------------------

- **Accuracy Score:** 0.9511
- **Precision Score:** 0.9544
- **Recall Score:** 0.9452
- **F1 Score:** 0.9498

Random Forest
----------------------------------------------------

- **Accuracy Score:** 0.9748
- **Precision Score:** 0.9804
- **Recall Score:** 0.9677
- **F1 Score:** 0.9740

Gradient Boosting
----------------------------------------------------

- **Accuracy Score:** 0.9700
- **Precision Score:** 0.9739
- **Recall Score:** 0.9645
- **F1 Score:** 0.9692

K Nearest Neighbours
----------------------------------------------------

- **Accuracy Score:** 0.9811
- **Precision Score:** 0.9822
- **Recall Score:** 0.9822
- **F1 Score:** 0.9822

Support Vector Machine
----------------------------------------------------

- **Accuracy Score:** 0.9826
- **Precision Score:** 0.9880
- **Recall Score:** 0.9792
- **F1 Score:** 0.9836

Logistic Regression
----------------------------------------------------

- **Accuracy Score:** 0.9811

Ensemble
----------------------------------------------------

In this model, we predicted the output using 3 different base models: SVM, KNN, and Logistic Regression.

- **Accuracy Score:** 0.9874
- **Precision Score:** 0.9910
- **Recall Score:** 0.9852
- **F1 Score:** 0.9881