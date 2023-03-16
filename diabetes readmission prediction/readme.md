# diabetes readmission prediction

## Introduction

In the competition, it's required to predict the whether an inpatient is readmitted within 30 days given info about the encounter.


## Dataset

Our dataset is: Diabetes 130-US hospitals for years 1999-2008 Data Set.

Source: https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-800

The dataset represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It includes over 50 features representing patient and hospital outcomes.


The target labels, indicating: Days to inpatient readmission. 
- “<30” if the patient was readmitted in less than 30 days
- “>30” if the patient was readmitted in more than 30 days
- “No” for no record of readmission.

This problem is a multiclass classification problem.

Conclusion

The baseline model was Decision tree classifier

F1 Score (micro): 0.58

The final result on unseen data using LGBM classifier.

F1 Score (micro): 0.7436