# Credit_Risk_Analysis

## Overview

This project was designed to analyze different supervised machine learning alogrithms to understands pros/cons of each scenarios.  This ML was classification of people who were either "high" or "low" risk applicants for loans.

## Results

### Naive Random Sampling
![image](https://user-images.githubusercontent.com/107078763/194195605-05e24384-1ea9-4f78-8942-2de0a3793880.png)

### Smote Oversampling
![image](https://user-images.githubusercontent.com/107078763/194195731-67339c18-70e5-47f3-8982-3c9d67ccf935.png)

### Undersampling
![image](https://user-images.githubusercontent.com/107078763/194195793-4a0a3a8f-675f-4e3f-961b-cdef4e945b23.png)

### Combo Over/under sampling
![image](https://user-images.githubusercontent.com/107078763/194195837-93c21db2-b000-4d36-9cbe-04b0a21df2b1.png)

### Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/107078763/194195909-46fd30e4-a773-41e7-99f5-c2a08771cc52.png)

### East Ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/107078763/194195985-9e83b857-7602-4965-b19a-46d97b518317.png)


## Summary
These models display different cases of whether to classifiy an applicant as "high" or "low" risk.  The classification report displays precision and recall %s to judge the accuracy of each model.  Precision is the predicts the number of true positives to total predicted positives.  Recall predicts  true positives to total actual positives in the data. High Recall rates means that the banks are falsey detecting customers as high risk when they are not.  F1 scores are a balanced prediction of precision or recall so I would utilize Balanced Random Forest Classifier if I needed to use a model to predict credit risk because the balanced score is 95%. Even though we may lose business to false negatives, this model has the best chance of predicting good credit.
