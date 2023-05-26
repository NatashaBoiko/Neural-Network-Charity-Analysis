# Neural-Network-Charity-Analysis

## Overview

Using knowledge of machine learning and neural networks, use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

Metods used:

- Preprocessing the data for the neural network model
- Compile, train and evaluate the model,
- Optimize the model.


### Data Preprocessing

- EIN and NAME are identification information and have been removed from the input data.
- The column IS_SUCCESSFUL contains binary data showing if charity donation was used effectively. This is a target for our deep learning neural network.
- APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features for our model.
- Encoding of the categorical variables, spliting into training and testing datasets and standardization have been applied to the features.


### Summary

- The deep learning neural network model did not reach the target of 75% accuracy. Considering that this target level is pretty average we could say that the model is not outperforming.
- Since we are in a binary classification situation, we could use a supervised machine learning model such as the Random Forest Classifier to combine a multitude of decision trees to generate a classified output and evaluate its performance against our deep learning model.
