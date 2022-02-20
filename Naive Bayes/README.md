# Navie Byase Notes and code
## Results and conclusion 

1) In this project, I build a Gaussian Naïve Bayes Classifier model to predict whether a person makes over 50K a year. 
2) The model yields a very good performance as indicated by the model accuracy which was found to be 0.8083.
3) The training-set accuracy score is 0.8067 while the test-set accuracy to be 0.8083. These two values are quite 
   comparable.So, there is no sign of overfitting.
4) I have compared the model accuracy score which is 0.8083 with null accuracy score which is 0.7582.
   So, we can conclude that our Gaussian Naïve Bayes classifier model is doing a very good job in predicting the class labels.
5) ROC AUC of our model approaches towards 1. So, we can conclude that our classifier does a very good job 
   in predicting whether a person makes over 50K a year.
6) Using the mean cross-validation, we can conclude that we expect the model to be around 80.63% accurate on average.
7) If we look at all the 10 scores produced by the 10-fold cross-validation, we can also conclude that there is a relatively
   small variance in the accuracy between folds, ranging from 81.35% accuracy to 79.64% accuracy. So, we can conclude that 
   the model is independent of the particular folds used for training.
8) Our original model accuracy is 0.8083, but the mean cross-validation accuracy is 0.8063. 
   So, the 10-fold cross-validation accuracy does not result in performance improvement for this model.

