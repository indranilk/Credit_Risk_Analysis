# Credit_Risk_Analysis

Overview

In this challenge we created different machine learning models to help predict credit risk. We used different techniques to train and evaluate different models. Some of the techniques that we used are undersampling, oversampling, combination sampling. In the first section we used resampling techniques by training model, calculating balanced accuracy scores, confusion matrix, and imbalanced classification report. In the second section we used the SMOTEEN algorithm with over and under sampling to predict the risk. In the third section we performed basic data cleaning and used ensemble classifiers and balanced random forest classifiers algorithm to help predict the risk. 

Results

Naïve Random Oversampling
![image](https://user-images.githubusercontent.com/8925001/131294881-11f4dd02-0c87-40e6-a415-a9baaa01bbf7.png)

•	The balanced accuracy score is 0.64
•	The high risk category has lower precision and higher recall 
•	The low risk category has higher precision and higher recall.

SMOTE Oversampling
![image](https://user-images.githubusercontent.com/8925001/131294925-e971cb35-9d9d-484d-b3a5-3b15d08e519f.png)

•	The balanced accuracy score is 0.62.
•	The high risk category has lower precision and higher recall.
•	The low risk category has higher precision and higher recall.

UnderSampling
![image](https://user-images.githubusercontent.com/8925001/131294982-3f94fe1c-a3b9-401a-aa43-91e875765de9.png)

•	The balanced accuracy score is 0.62. 
•	The high risk category has low precision and higher recall.
•	The low risk category has high precision and lower recall.

Combination (Over and Under Sampling)
![image](https://user-images.githubusercontent.com/8925001/131295052-776aae6b-3e89-4757-95b3-363ccfbcdec9.png)

•	The balanced accuracy score is 0.62.
•	The high risk category has really low precision and higher recall.
•	The low risk category has high precision and higher recall.

BalancedRandomForestClassifiers
![image](https://user-images.githubusercontent.com/8925001/131295142-19b5716b-c3e8-424d-8867-ec79b3a18d73.png)

•	The balanced accuracy score is 0.9994
•	All categories have high recall value
•	The low risk and weighted average have high precision value

Easy Ensemble ADA Classifier
![image](https://user-images.githubusercontent.com/8925001/131295221-9049fdcd-64a6-42ef-9cd0-ab6dc4022231.png)

•	The balanced accuracy score is 0.50.
•	All categories have high precision and recall value.

Summary	

All balanced accuracy scores are at least 0.50. The highest precision and recall values are 1.00. The lowest value is 0.01. Most of the values are 0.61 and 0.63. I would recommend the Easy Ensemble ADA Boost Classifier as that has the highest precision and recall values. All scores are 1.00 which shows 100% accuracy.


