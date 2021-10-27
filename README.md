# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:
Credit risk is an inherently unbalanced classification problem. Good loans easily outnumber risky loans so we needed to employ different techniques to train and evaluate models with unbalanced classes. We used libraries to build and evaluate models using resampling. We used the credit card credit dataset from LendingClub and we oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then we used a combinatorial approach of over- and undersampled using the SMOTEENN algorithm. We then compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predicy credit risk. Lastly we evaluated the performance of these models.


## Results:

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)

## Summary:

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
