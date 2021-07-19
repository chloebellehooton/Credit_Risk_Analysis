# Credit Risk Analysis

## Overview of the loan prediction risk analysis:

The purpose of this analysis is well defined (4 pt)
The purpose of this analysis was to test if machine learning can be used to predict credit risk. It will hopefully provide a quicker and more reliable experience. Machine Learning will in theory be more accurate and therefore lead to less loan default rates. I built and evaluated several marine learning models / algorithms to evaluate their performance and see how well they predict the loan data. 


## Results:


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

The goal of this analysis was to evaluate all loans but the more compelling information would be to be able to use machine learning to evaluate the high risk loans that create financial risk for the bank. All of the models had quite a high precision rate for low risk loans but unfortunately had very low precision rates for the high risk loans. Despite the fairly high accuracy rates, the low precision scores for the high risk loans throw out most of the models. 

The Easy Ensemble AdaBoost Classifier would be my recommendation going forward given it had the highest recall/sensitivity for the high risk loans. 

