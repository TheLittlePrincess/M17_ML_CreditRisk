#Module 17 Challenge
# Credit Risk
## Overview
Using a credit dataset, the goal in this challenge is to use different techniques to train and evaluate models with unbalanced classes to apply machine learning to help Jill evaluating credit risks, that is, if those are proven to be reliable.

## Results
## Deliverable 1 - Resampling Models to Predict Credit Risk
•	Naive Random Oversampling
![ Naive Random Oversampling]( https://github.com/TheLittlePrincess/M17_ML_CreditRisk/blob/main/Results/D1_1_Naive%20Random.png)


•	SMOTE Oversampling
![SMOTE Oversampling]( https://github.com/TheLittlePrincess/M17_ML_CreditRisk/blob/main/Results/D1_2_Smote.png)

•	ClusterCentroids
![ ClusterCentroids]( https://github.com/TheLittlePrincess/M17_ML_CreditRisk/blob/main/Results/D1_3_cluster.png)

## Deliverable 2 - SMOTEENN algorithm to Predict Credit Risk
SMOTEENN algorithm![ SMOTEENN]( https://github.com/TheLittlePrincess/M17_ML_CreditRisk/blob/main/Results/D2_Smoteenn.png)


## Deliverable 3 - Ensemble Classifiers to Predict Credit Risk
•	BalancedRandomForestClassifier
![ RandomForestClassifier]( https://github.com/TheLittlePrincess/M17_ML_CreditRisk/blob/main/Results/D3_1_RandomForest.png)


•	Features sorted in descending order by feature importance
![ sample of features sorted]( https://github.com/TheLittlePrincess/M17_ML_CreditRisk/blob/main/Results/D3_1_RandomForest_FeaturesSorted.png)

•	EasyEnsembleClassifier algorithm
![ EasyEnsembleClassifier algorithm]( https://github.com/TheLittlePrincess/M17_ML_CreditRisk/blob/main/Results/D3_2_EasyEnsambleClassifier(eec).png)


## Summary
There was virtually no difference between the Naïve and Smote models, both with precision scores of ~0.65. The one coming up from combining wasn’t better with a recall of 0.69 and a F1 score of 0.01 (The other two had 0.02). Neither model recommended.

As per the RandomForest, precision is low at 0.03 with an F-1 low score at 0.06. The Easy Ensamble Classifier was the best out of the machine learning models we tried: with 0.92 recall, accuracy score of 0.94 and F-1 at 0.16; yet, none of the models applied in this challenge seem to be at an optimal level – in other words not accurate enough for Jill to use to make her credit risk decisions.

