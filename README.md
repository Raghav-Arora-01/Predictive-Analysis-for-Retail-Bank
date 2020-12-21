# MACHINE LEARNING IN RETAIL BANKING
[![author](https://img.shields.io/badge/author-Raghav-ff69b4.svg?style=flat-square)](https://www.linkedin.com/in/raghav-arora-bb7a46115/)

### Objectives of Research
Analytics is helping the banking industry become smarter in managing the myriad challenges.
Challenges:
- What is a suitable product to recommend to a customer?
- What is the best time to market the product?
- Which is the most effective channel to contact a customer?

The data is related with direct marketing campaigns of a banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

### Problem Statement
The data-set is related with direct marketing campaigns (were based on phone calls) of a banking institution. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The goal is to predict if the client will subscribe a term deposit.

### Graphs
#### ROC AUC CURVES
 
![15](https://github.com/Raghav-Arora-01/Predictive-Analysis-for-Retail-Bank/blob/main/Images/15.PNG)
![14](https://github.com/Raghav-Arora-01/Predictive-Analysis-for-Retail-Bank/blob/main/Images/14.PNG)
![13](https://github.com/Raghav-Arora-01/Predictive-Analysis-for-Retail-Bank/blob/main/Images/13.PNG)

## Conclusion
Most classification problems in the real world are imbalanced. Also, almost always data sets have missing values. In this post, we covered strategies to deal with both missing values and imbalanced data sets. We also explored different ways of building ensembles in sklearn. Below are some takeaway points:

- Sometimes we may be willing to give up some improvement to the model if that would increase the complexity much more than the percentage change in the improvement to the evaluation metrics.

- When building ensemble models, try to use good models that are as different as possible to reduce correlation between the base learners. We could’ve enhanced our stacked ensemble model by adding Dense Neural Network and some other kind of base learners as well as adding more layers to the stacked model.

- Easy Ensemble usually performs better than any other resampling methods.


### Columns:
* age
* job
* marital
* education
* default
* balance	
* housing	
* loan
* contact
* day
* month
* duration
* campaign
* pdays
* previous
* poutcome
* deposit: field used to split the data into two sets (client has deposited, or not)
