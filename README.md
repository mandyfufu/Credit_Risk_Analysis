# Module 18 challenge: SML and Credit Risk

Overview:
The objective of this analysis is to assess credit risk for a credit card dataset from LeandingClub. Credit risk is inherently an unbalanced classification problem, because good loans usually outnumber risky ones. We’ll leverage the imbalance-learn and scikit-learn library to build and evaluate the dataset with 6 ML models.  

Results:
Oversampling  results - 
Accuracy score: 66.28%
Avg. precision: 99%
Avg. recall: 64%

SMOTE results - 
Accuracy score: 65.84%
Avg. precision: 99%
Avg. recall: 68%

Undersampling results - 
Accuracy score: 53.14%
Avg. precision: 39%
Avg. recall: 67%

Over and under - 
Accuracy score: 67.90%
Avg. precision: 99%
Avg. recall: 59%
		
Balanced Random Forest - 
Accuracy score: 78.85%
Avg. precision: 99%
Avg. recall: 87%

Easy Ensemble - 
Accuracy score: 93%
Avg. precision: 99%
Avg. recall: 94%

Summary: 
Of the 6 models we ran the data through, the most promising are the results from  the Easy Ensemble Classifier. All the other models don't yield a confidence in recommendation but that’s probably due to the nature of the imbalance of data. The best model that would minimize loan risk is the Easy Ensemble Classifier. 
