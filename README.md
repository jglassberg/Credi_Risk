# Credit_Risk_Analysis

Analysis Overview:
This challenge required us to do a detailed analysis of LendingClub's credit card data. It was our responsibility to:
  1. Use resampling models to predict credit risk. 
  2. Use the SMOTEENN Algorithm to predict credit risk.
  3. Use Ensemble Classifiers to predict credit risk. 

Results: 
Random Sampling Model

The balance accuracy score came to 65% whereas the high-risk percision is about 1% only with 62% sensitivity which makes f1 of 2%. Although the low_risk population resulted in a high number with a precision of almost 100% and a sensitivity of 69%

SMOTE Model

This model did not produce much of a difference than the Random Sampling model. the high_risk precision resulted in 1% with 63% sensitivity. It can be deduced that due to the increased number of false positives, the low_risk sensitivity is only 40%.

SMOTEENN Model

The balanced accuracy score is about 62% and the high_risk precision is still 1% only with 68% sensitivity which makes a f1 of only 2%. Additionally the high number of false positives, the low_risk sensitivity is 57%.

Balanced Random Forest Model

The balanced accuracy score improved to about 79%, whereas the high_risk precision is still low at 4% only with 67% sensitivity which makes a F1 of only 7%. Due to a lower number of false positives, the low_risk sensitivity is now 91% with 100% presicion.

Easy Ensemble Model

This model produced a 93% balanced accuracy score. The high_risk precision came in rather low around 7% with a 91% sensitivity which makes a f1 only 14%. This test resulting ina  low number of false positive, the low_risk sensitivity is now 94% with 100% precision. 


