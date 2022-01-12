# Assignment2

K-Nearest-Neighbors-Social-Network-Ads
Using K-Nearest Neighbors model to predict if a person is going to buy a new car or not based on the available data

Problem
Suppose a company is going to launch a new campaign for their new brand of car and want to know which category of people are likely to buy their brand new car so they can have the ads that target those peoples. For this they contacted a social network advertising company which have the data from another similar successful campaign. Now, they want to make a model which helps achieve their goal.

Dataset
The dataset contains 400 entries which contains the userId, gender, age, estimatedsalary and the purchased history. The matrix of features taken into account are age and estimated salary which are going to predict if the user is going to buy new car or not(1=Yes, 0=No).

Solution
First the pre-processing of data is done and then the prediction was done using K-Nearest Neighbors (K-NN) followed with visualization. The dataset is split into 75/25 ratio (training set = 0.75 & test set = 0.25).

The confusion matrix below shows that our model predicts 93 correct and 7 wrong decisions which shows 93% accuracy.

Confusion Matrix kNN

The data visualization of the training set and test set is given below. As k nearest neighbors is non-linear classifier, the graph is non-linear (curve). The green dots shows the people buying the car whereas red dots shows the people not buying the car. The green dots on the green region shows the true positive whereas the red dots on the red region shows the true negative. The wrongly classified are the green dots in the red region (false negative) and the red dots in the green region (false positive).

knn (training set)

knn (test set)
