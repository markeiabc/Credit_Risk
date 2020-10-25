# Credit_Risk

The objective of this analysis was to evaluate multiple machine learning models to determine which would provide the best prediction of whether a loan was good or bad without overfitting. I used used resampleing to evaluate the effectiveness of the models used. 

## Recommendation
Based on the models run, the precision score was consistent across all, keeping an average of 99%. From a recall perspective, undersampling provided the lowest result, indicating it will have more opportunity of not identifying high-risk loans than the other methods. I would recommend using the combination (over and under) sampling method. It provides that most balanced scores and has the highest balanced accuracy score. Given the balanced accuracy score is used to say how much someone could in a sense, "trust" the model, we should go with what provides the most accuracy. Second in line would be oversampling. 

### Oversampling

#### Naive Random Oversampling
- Precision Score
  - High_risk: 2%
  - Low_risk: 100%
  - Average: 99%
- Recall Score
  - High_risk: 72%
  - Low_risk: 72%
  - Average: 72%
- Balanced Accuracy Score: 73.31%

#### SMOTE Oversampling
- Precision Score
  - High_risk: 2%
  - Low_risk: 100%
  - Average: 99%
- Recall Score
  - High_risk: 73%
  - Low_risk: 73%
  - Average: 73%
- Balanced Accuracy Score: 72.63%

### Undersampling
- Precision Score
  - High_risk: 1%
  - Low_risk: 100%
  - Average: 99%
- Recall Score
  - High_risk: 66%
  - Low_risk: 74%
  - Average: 66%
- Balanced Accuracy Score: 70.16%

### Combination (Over and Under) Sampling 
- Precision Score
  - High_risk: 2%
  - Low_risk: 100%
  - Average: 99%
- Recall Score
  - High_risk: 73%
  - Low_risk: 75%
  - Average: 73%
- Balanced Accuracy Score: 73.99%

