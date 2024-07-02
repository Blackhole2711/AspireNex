# Credit-Card-Fraud-Detection

I have trained and created a non-linear classifier based on logistic regression to classify the legitimate transactions and fraudulent transactions.
First I created a Data Frame of the data given to us and then used various plotting techniques to understand the data.
Now time and transaction amount do not play a vital role in this classification because of two reasons. As the time of fraud and the transaction amount can only be predicted for a particular used based on his/her previous transaction. For a large variety of users it has no use in this classification.
Then I plotted the correlation matrix to know the correlation between all the features of the given data.
Then I used SMOTE(uses oversampling of minority class, in this case oversampling the fraudulent transactions) to overcome the class imbalance, as the dataset was highly imbalanced followed by splitting the training and testing data with training data being 30% of the complete dataset.
Then I computed the best parameter for the classifier using logistic regression.
Finally I tested the classifier on the testing data with the help of roc curve and by computing the accuracy of the model.
The ROC AUC value of 0.9846457343012589 and accuracy of 98.57% shows that the classifier classifies the legitimate and fraudulent transactions almost perfectly.
 


