# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:

The purpose of this analysis is well defined (4 pt)



## Results:
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)
### 1. Naive Random Oversampling
- The model is 65% accurate and it is 100% precise for low risk loans with a 67% sensitivity. The high risk loans were 1% precise with a 63% sensitivity.
![image 1](https://github.com/chloebellehooton/Credit_Risk_Analysis/blob/main/images/naive_random_oversampling.png)

### 2. SMOTE Oversampling
- The model is 65% accurate and it is 100% precise for low risk loans with a 66% sensitivity. The high risk loans were 1% precise with a 64% sensitivity.
![image ](https://github.com/chloebellehooton/Credit_Risk_Analysis/blob/main/images/SMOTE_oversampling.png)

### 3. ClusterCentroids Undersampling
- The model is 51% accurate and it is 100% precise for low risk loans with a 47% sensitivity. The high risk loans were 1% precise with a 56% sensitivity.
![image ](https://github.com/chloebellehooton/Credit_Risk_Analysis/blob/main/images/undersampling.png)

### 4. Combination (Over and Under) Sampling: SMOTEENN
- The model is 51% accurate and it is 100% precise for low risk loans with a 47% sensitivity. The high risk loans were 1% precise with a 56% sensitivity.
![image ](https://github.com/chloebellehooton/Credit_Risk_Analysis/blob/main/images/SMOTEENN.png)

### 5. Balanced Random Forest Classifier
- The model is 78% accurate and it is 100% precise for low risk loans with a 91% sensitivity. The high risk loans were 4% precise with a 67% sensitivity.
![image ](https://github.com/chloebellehooton/Credit_Risk_Analysis/blob/main/images/balanced_random_forest_classifier.png)

### 6. Easy Ensemble AdaBoost Classifier
- The model is 91% accurate and it is 100% precise for low risk loans with a 94% sensitivity. The high risk loans were 7% precise with a 91% sensitivity.
![image ](https://github.com/chloebellehooton/Credit_Risk_Analysis/blob/main/images/Easy_Ensemble_AdaBoost_Classifier.png)




## Summary:

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
