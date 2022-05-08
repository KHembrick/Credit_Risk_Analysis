# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:
* The puropse of this analysis is to employ different techniques to train and evalute models with unbalanced classes. Using Machine Learning and the credit card dataset from the Lending Club, a peer-to-peer lending service. Upon completion of the analysis I will be tasked with making a recommendation on whether they should be used to predict credit risk.

## Results
In the charts below I compared oversampling/undersampling algorithms and Naive Random oversampling Model and the SMOTE Model.
Naive Random Oversampling

![percentage random](https://user-images.githubusercontent.com/96032255/167318195-ede35d28-f3d0-49c6-8df2-954e59d2b6c5.PNG)
![rnadom oversampling 1](https://user-images.githubusercontent.com/96032255/167318202-011e51e6-d24d-46e5-a866-61c7d3d1331f.PNG)
* There are more Low risk applications than there are High Risk. 
* The Balance accuracy percentage is at 64%.

SMOTE Oversampling
![SMOTE over sampling](https://user-images.githubusercontent.com/96032255/167318304-909f7716-2070-431e-a95c-11c99edfe446.PNG)
![SMOTE percentage](https://user-images.githubusercontent.com/96032255/167318305-5e4f22d6-534a-411b-b7d6-88aaaf40381f.PNG)

* There are also more Low risk applications than there are High Risk.
* The Balance accuracy percentage is at 66%.
* the numbers look very similar to the Naive oversampling with with SMOTE Oversampling showing a 2% difference in the geo and iba.

Undersampling
![under perc](https://user-images.githubusercontent.com/96032255/167318422-44b5da5a-2b00-4900-8230-11020942975b.PNG)
![under](https://user-images.githubusercontent.com/96032255/167318442-4fc0424c-11d4-4d13-9ab2-be2c57e08217.PNG)

* In the chart above you will notice that the risk is much higher than the other charts. 
* The balance accuracy score percentage is only 54%.

Balance Rand Forest Classifiers
![ems perc](https://user-images.githubusercontent.com/96032255/167318665-2fca8c99-cc70-49dd-ac07-37ed75240a1d.PNG)
![ensemble](https://user-images.githubusercontent.com/96032255/167318673-b18a32b9-2125-4bf0-9832-e5f1ac60659d.PNG)

* The imbalaced classification report for this model shows that the risk is also lower than higher.
* the balance accuracy score improved and is 79%.

Easy Ensemble AdaBoost Classifier
![easy percnetage](https://user-images.githubusercontent.com/96032255/167318888-a5bac765-b515-48e7-91e1-350d176c6aea.PNG)
![easy](https://user-images.githubusercontent.com/96032255/167318892-23c33899-9486-4fa0-8abf-846241e22ec8.PNG)


* The Risk overall for this model is also low.
* The balance accuracy rate score is at 93% which is better than all the other models.

## Summary
The results of this analysis and all the models that were used are not impressive to me. Personally I would not recommend any of these models. On the other hand the best model out of all of the models used would be the Easy Ensemble AdaBoost Classifier model. Which has the highest scores and percentages of 93%. The numbers are not great enough or accurate enough to be used to predict credit risk accurately and efficiently.
