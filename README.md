# Credit_Risk_Analysis

##**Overview**

The purpose of the project is to carry out a comparativeof different data modelling techniques of supervised machine learning using various algorithms for the data set provided by Lending-Club.

Following techniques were used for analysis:
* Naive Random (Oversampling technique)
* SMOTE (Oversampling technique)
* Cluster Centroids ( Undersampling technique)
* SMOTEENN(over + undersampling technique)
* Balanced Random Forest Classifier (technique to reduce bias)
* Easy Ensemble AdaBoost Classifier (technique to reduce bias)


##**Results**

The results of all models used for supervised machine learning techniques are as follows:

* Naive Random Oversampling
i. Accuracy: 0.65
ii. Precision: 0.99
ii. Recall: 0.56

* SMOTE Oversampling
i. Accuracy:0.65
ii. Precision:0.99
ii. Recall: 0.69

* Cluster Centroids Undersampling
i. Accuracy: 0.54
ii. Precision: 0.99
ii. Recall:0.54

* SMOTEENN(over + undersampling technique)
i. Accuracy:0.64
ii. Precision:0.99
ii. Recall:0.57

* Balanced Random Forest Classifier
i. Accuracy:0.78
ii. Precision: 0.99
ii. Recall: 0.89

* Easy Ensemble AdaBoost Classifier
i. Accuracy: 0.93
ii. Precision: 0.99
ii. Recall: 0.94


##**Summary**

Although the precision for all 6 techniques is almost same at 0.99, it is preferable to use the Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier for the analysis due to their high accuracy at 0.78 and 0.93 respectively. They also have relatively higher recall values at 0.89 and 0.94 respectively.

Between the above two, Easy Ensemble AdaBoost Classifier has an exceedingly good combination of very high accuracy (0.93), precision (0.99) and highest recall value(0.94) implying it is the best Supervised Machine Learning.