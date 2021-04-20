# Neural_Network_Charity_Analysis

## Overview of Analysis

Analyzed a dataset using different machine learning models, such as the *Random Forest Classifier, Support Vector Machine, and the Logistic Regression model*, all compared to the neural network deep learning model. Endeavored to find out if a given person would be eligible for a loan based on credit history.

## Results

* *Data Preprocessing

  - The target variables for the models were the IS_SUCCESSFUL feature of the dataset. This was what I wanted to predict.
  - The features for my model were CLASSIFICATION and APPLICATION_TYPE, used to predict credit security.
  - Removed STATUS, INCOME_AMOUNT, and SPECIAL_CONSIDERATIONS features from the dataset prior to running the ML model because these weren't needed for the analysis.

* *Compiling, Training, and Evaluating the Model

  - Chose three hidden layers with 80 neurons in the first layer, 50 in the second, and 20 in the third.
  - I was not quite able to hit the target performance percentage of 75%
  - Attempting to increase model performance, I increased the number of layers from 2 to 3, increased the number of neurons in each layer, and cut out certain noisy features in the dataset.

## Summary

Overall the results were the same in the optimized deep learning model as the previous un-optimized model, at about 72% predictive accuracy.

![results](https://github.com/Kyle2Miles93/Neural_Network_Charity_Analysis/blob/main/Resources/Results_predictive%20_accuracy.png)

* This image shows the results after changing the number of neurons in each layer as well as increasing the hidden layer count + 1.
* Another model that could solve this problem could be the Random Forest Classifier because it operates much like a deep learning model but faster. It gathers multiple decision trees and puts them together for a usually dependable prediction level. 
