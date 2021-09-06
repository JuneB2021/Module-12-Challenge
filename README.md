# Module 12 Report Template

## Overview of the Analysis

Credit risk poses a classification problem that’s inherently imbalanced due to the outnumber of healthy loans vs. risky loans. The purpose of the analysis is to build a model that can help identify the creditworthiness of borrowers.

### Data

Using historical data set of Loan size, Interest rate, Income, Total debt, Debt-to-Income Ratio, Total number of Accounts, Derogatory Marks to predict the high-risk loan vs. healthy loan.

      ### Total Loan count: 77,536
      ### Healthy Loan count: 75,036 
      ### High-Risk Loan count: 2,500

### Prediction Process

* Split the Data into Training and Testing Sets

* Create a Logistic Regression Model with the Original Data

* Predict a Logistic Regression Model with Resampled Training Data 

### Prediction Method

* **Logistic Regression Model** - use regression algorithms to model and predict continuous variables
* **Logistic Regression Model Resampled Training Data** - use oversampling method to balance the original instances from smaller class equal to the size of the larger class in the training set 

-------

## Results

* **Machine Learning Model 1(Logistic Regression Model):**
  * Balance Accuracy score: 95%
  * Prediction of 100% accuracy on healthy loan and 85% accuracy on high-risk loan
  * Recall scores of high-risk loan: 0.91



* **Machine Learning Model 2(Logistic Regression Model with Oversampling data):**
  * Balance Accuracy score: 99%
  * Prediction of 100% accuracy on health loan and 84% accuracy on high-risk loan
  * Recall scores of high-risk loan: 0.99 

-------

## Summary

The result of 2 models indicated only 1% variance of the accuracy on high-risk loan eventhough the Oversampling method overall Balance Accuracy Score was 4% higher and 0.08 in Recall scores. Both models also show 100% accuracy on healthy loan which account for over 95% of total data populations, as a result, Model 1 is good enough to use for the prediction.

It's important to predict the `1`'s; however, it was only 3.2% of total loans from the entire population that considered high risk loans.
