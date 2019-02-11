# Kaggle-Titanic-Machine-Learning-from-Disaster
Information about the competition: https://www.kaggle.com/c/titanic
The goal is to predict survival on the Titanic and get familiar with ML basics.
I used 3 groups of algorithm containing Tree base model (decision tree, random forest, gradient boosting machine),
Support vector machine (with rbf and linear kernel), Neural Network (from simple nets to very deep nets), 
associated with the tool GridSearchCV in Scikit-Learn pakage (Python) to find the best hyperparameter. 
On the training set, i obtained normally 86% - 90% accuracy while validation set 82-84%. 
But when i submitted the test set i got maximum ~81% accuracy in leaderboard for many times submission with different models. 
I realized that it’s not easy to obtain very high accuracy in test set because the number of data in traning set is not so much 
(900 comparing with 400 passenger id in test set), and the distribution between them seems to different. 
I tryed blending and stacking but the results was not improved.