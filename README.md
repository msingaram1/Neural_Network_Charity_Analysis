### Neural_Network_Charity_Analysis

## Overview

The purpose of this analysis is creating a neural network to predict if applicants will be successful if funded by Alphabet Soup. A dataset containing greater than 34K organization that have previously received funding from Alphabet Soup is used to train and evaluate data to make a decision regarding which applicants are successful. 

## Results 

# Data Preprocessing
- EIN & NAME columns removed
- IS_SUCESSFUL column contains data regarding whether data is used effectively or not which is used as target for neural network
- Features are Affiliation, Classification, Use_Case, Organization, Income_AMT, Special_Consideration, Status, Ask_AMT, Application_Type
- 
# Compiling, Training, and Evaluating the Model
- The optimized model is made with 75 and 25 nuerons in the two hidden layers respectively which Relu activation functions used for the hidden layers and for the ouput layer Sigmoid is used.
- The model accuracy is 53%, well under the target accuracy of 75%.
- The number of nuerons was increased for both layers to increase model performance (from 31% to 53%)

## Summary

The model does not have an accuracy of 75%. Since the target level is quite average we can determine that the model is not outperforming. Perhaps using the Random Forest Classifier, a supervised machine learning model, would yield better results. 
