# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:
Credit risk is an inherently unbalanced classification problem. Good loans easily outnumber risky loans so we needed to employ different techniques to train and evaluate models with unbalanced classes. We used libraries to build and evaluate models using resampling. We used the credit card credit dataset from LendingClub and we oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then we used a combinatorial approach of over- and undersampled using the SMOTEENN algorithm. We then compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predicy credit risk. Lastly we evaluated the performance of these models.


## Results:
### Naive Random Oversampling
- Accuracy Score: 64.6%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 69%
- Recall Low Risk: 60%

![myTest](https://github.com/nfreeman19/Credit_Risk_Analysis/blob/main/Visuals/1%20-%20Naive%20Random%20Oversampling.png)

### SMOTE Oversampling
- Accuracy Score: 65.2%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 62%
- Recall Low Risk: 68%

![myTest](https://github.com/nfreeman19/Credit_Risk_Analysis/blob/main/Visuals/2%20-%20SMOTE%20Oversampling.png)

### Undersampling
- Accuracy Score: 65.2%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 69%
- Recall Low Risk: 40%

![myTest](https://github.com/nfreeman19/Credit_Risk_Analysis/blob/main/Visuals/3%20-%20Undersampling.png)

### Combination (Over and Under) Sampling
- Accuracy Score: 54.4%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 72%
- Recall Low Risk: 57%

![myTest](https://github.com/nfreeman19/Credit_Risk_Analysis/blob/main/Visuals/4%20-%20Combination%20(Over%20and%20Under)%20Sampling.png)

### Balanced Random Forest Classifier
- Accuracy Score: 74.5%
- Precision High Risk: 3%
- Precision Low Risk: 100%
- Recall High Risk: 62%
- Recall Low Risk: 87%

![myTest](https://github.com/nfreeman19/Credit_Risk_Analysis/blob/main/Visuals/5%20-%20Balanced%20Random%20Forest%20Classifier.png)

### Easy Ensemble AdaBoost Classifier
- Accuracy Score: 93.1%
- Precision High Risk: 9%
- Precision Low Risk: 100%
- Recall High Risk: 92%
- Recall Low Risk: 94%

![myTest](https://github.com/nfreeman19/Credit_Risk_Analysis/blob/main/Visuals/6%20-%20Easy%20Ensemble%20AdaBoost%20Classifier.png)


## Summary:

Most of the results were all over the board however the Easy Esemble had the highest accuracy rate while all of the others stayed in the range of 50%-75%. All of the models provide a precision low rosk of 100%. My recommendation model would be the Easy Ensemble AdaBoost Calssifier. This had the highest accurancy score and the most balanced risks.
