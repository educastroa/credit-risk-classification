# Module 12 Report Template

## Overview of the Analysis

* The purpose of this analisys is to understand how accurately the regular logistic regretion model and the oversized logistic regretion model can predict high and low risk class loans.

* The financial information used as sample data is high and low risk loan information. The goal was to create a accurate model to predict high and low risk loans.

* We went through reading and undestanding the csv file. Subsequently, spliting the data between test and train data. Next, instantiating the a logistic regreation model fitting the train data. Finally, made predictions using the test data previously split and verifying the model accuracy for both oversized and original data 

* We used both regular data and oversized data to fit the logistic regretion model

## Results

* Regular Machine Learning Model 1:
  * Accuracy - 94%, Precision class 0 - 100%, Precision class 87% and Recall scores 94%.



* Oversized Machine Learning Model 2:
  * Accuracy - 96%, Precision class 0 - 100%, Precision class 87% and Recall scores 100%.

## Summary

* THe oversized model seem to be more reliable when trying to predict low and high risk loans. Not only it has higher accuracy, scoring 96% on balanced accuracy but it scores higher on recall as well.