# Module 20 Analysis Report for Credit Risk

## Overview of the Analysis


### purpose of the analysis.
Building a model that can accurately identify the creditworthiness of borrowers is crucial for lending services. Such a model allows lenders to evaluate the risk associated with lending to a particular borrower, set appropriate interest rates, and make well-informed decisions about loan approvals. By leveraging historical borrower data and various financial indicators, lenders can assess the probability of default and make more reliable lending decisions.

### Stages of the machine learning process - as part of this analysis.
The machine learning model design process began with ingesting the labels into a model to split the data into training and testing sets. To determine the loan lending creditworthiness of an individual I used a logistic regression.

## Results

* The classification report which takes into account the model's accuracy revealed that the healthy loans had a precision score of 100%, and a recall of 99%. 
* For the non-healthy loans, the precision and recall were 85% and 99%, respectively. 
* The overall performance of the model was calculated to be 99%.


## Summary

* Overall, the accuracy seems to be good enough to start exploring this kind of algorithms in a bank, however, I would prefer to start running a pilot with new data to assess model's reliability.
* It's important to note that the effectiveness of the creditworthiness model heavily depends on the quality and relevance of the data collected. Therefore, it's crucial to have a comprehensive and reliable dataset to achieve accurate predictions.
