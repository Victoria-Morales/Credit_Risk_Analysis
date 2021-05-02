# Credit Risk Analysis	 

## Overview of the Project
#### The purpose of this project is to use supervised machine learning models to predict the risk of extending credit to individuals.  In the project, I used various machine learning models and evaluated their performance by calculating their accuracy scores, generating confusion matrices, and printing out the imbalanced classification report for each model.
 
## Results
#### RandomOverSampler

![img1](/Resources/Random_Oversampler.png)

* Balanced Accuracy Score: 0.64
* Precision: 0.99
* Recall: 0.67

#### SMOTE

![img2](/Resources/Smote.png)


* Balanced Accuracy Score: 0.64
* Precision: 0.99
* Recall: 0.64


#### ClusterCentroids

![img3](/Resources/Cluster_Centroid.png)


* Balanced Accuracy Score: 0.53
* Precision: 0.99
* Recall: 0.45


#### SMOTEENN

![img4](/Resources/Smoteenn.png)


* Balanced Accuracy Score: 0.64
* Precision: 0.99
* Recall: 0.58

#### BalancedRandomForestClassifier

![img5](/Resources/Random_Forest.png)

* Balanced Accuracy Score: 0.79
* Precision: 0.99
* Recall: 0.87


#### EasyEnsembleClassifier

![img6](/Resources/Easy_Ensemble.png)

* Balanced Accuracy Score: 0.93
* Precision: 0.99
* Recall: 0.94


## Summary 
#### Most of the models performed at a similarly unimpressive accuracy level. However, the Random Forest Model and the Easy Ensemble Classifier had higher accuracy scores and would be preferable to use.
