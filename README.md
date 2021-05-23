# HeartAttackPrediction
## Table of content
1. [Demo](https://github.com/NaveenKumarMaurya/HeartAttackPrediction/blob/main/README.md#demo)
2. [Overview](https://github.com/NaveenKumarMaurya/HeartAttackPrediction/blob/main/README.md#overview)
3. [Motivation](https://github.com/NaveenKumarMaurya/HeartAttackPrediction/blob/main/README.md#motivation)
4. Technical Aspect
5. Installation
6. Run
7. Deployement on Jupyter Notebook
8. Directory tree
9. Technologies Used
10. License
11. Credit


## Demo
link :https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset
![](https://github.com/NaveenKumarMaurya/HeartAttackPrediction/blob/main/heart-attack-silent.jpg)

## Overview
This is a simple classification problem trained on python scikit-learn library.The classification model takes 
the independent variable eg. age,sex,cholestrol,blood pressure etc.,from heart attack data set to predict 
whether the person will get heart attack or not.In this project chi-squre test has been used for to check feature importance of categorical variable
and independent t-test is used to compare the mean of variables grouped on the basis of output category and by finding correlation among numerical 
variables to get the importance of each variable in deciding output.Features renaming also done with help of [google](https://archive.ics.uci.edu/ml/datasets/Heart+Disease/)
We also use Pipeline method to apply 10 classifiction algorithms(1.logistic Regression 2.Decisiontreeclassifier 3.Randomforestclassifier 4.GaussianNB 5.KNN 6.Gboost Classifier 7.AdaboostClassifier8.SGDClassifier 9.SVC 10.MLP Classifier) to get the best accuracy which i have got in KNN=82.4%.Then i also apply for loop to get the best random
state producing good accuracy and then we have got accuracy of 90% with choosing appropriate n_nieghour parameter.

## Motivation
In india, every year 30000 people get died from heart attack and this no increasing continuously every year
thats why i was very curious to know about the effect of factors which causes the  heart attack and what is inter relation among  the independent variables

