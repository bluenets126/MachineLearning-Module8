# MachineLearning-Module8
Summary Lab for Machine Learning Course


Final lab for Class 7 Machine Learning.

Confusions:  Since we were given two data sets.  A link to the kaggle dataset and a given CSV file (which i think purposely has null values) I wasn't sure which to use.  I did exploratory data analysis on both datasets,                  however I only applied models to the first dataset.

Assumptions:  Only use file proved financial_loan_data.csv.
              Only need to either predict loan approval and/or Risk score
              If you're calculating Loan Approval or RiskScore, neither can be used as features in the calculations since they are heavily correlated and probably would not be there for future unseen data.
              80% 20% Training Testing split
              

In the scenarios in the lab, i decided to calculate base don the model the total value of lost money based on false positive and false negative.  False positives weighed more at cost value, so I created a custom metric, which uses 90% precision and 10% recall to minimize the total cost lost.  This is what ended up on the final model which is a SVM.
