# Credit_Risk_Analysis

# Overview
The purpose of this project was to predict high risk and low risk loans and determine which ML algorithm was most suited to the task.

# Results
In the results below, the precision and recall are specific to identifying high risk loans.

## Oversampling
### Native Random Oversampling
- Balanced accuracy score: 0.65
- Precision: 0.01      
- Recall: 0.62 

### SMOTE
- Balanced accuracy score: 0.63
- Precision: 0.01       
- Recall: 0.62

## Undersampling
### ClusterCentroids
- Balanced accuracy score: 0.51
- Precision: 0.01       
- Recall: 0.57

## Combination sampling
### SMOTEEN
- Balanced accuracy score: 0.64
- Precision: 0.01      
- Recall: 0.70 

## Ensemble learners
### Balanced Random Forest Classifier
- Balanced accuracy score: 0.79 
- Precision: 0.04       
- Recall: 0.67

### AdaBoost
- Balanced accuracy score: 0.92
- Precision: 0.07      
- Recall: 0.91

# Summary:
All of the algorithms demonstrated a higher recall score and a mucher lower precision score for identifying high risk loans. Overall, the best performing algorithms were the ensemble learners, Balanced Random Forest Classifier and AdaBoost, as well as the combination sampling algorithm SMOTEEN, but these still demonstrated a very low precision score which could lead to qualified applicants being denied loans.  If any of these three algorithms were used, they might be most appropriately used to streamline workflow by identifying applications that need further attention rather than having the final say in which loans are denied