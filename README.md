# Neural_Network_Charity_Analysis

## Overview
This project is to build a neural network model that can help predict the success of projects donated to by the Alphabet Soup Foundation. 

The model will use a data set of 34,000 donations Alphabet Soup has made in the past to try and learn to predict a project's success. The model will be considered successful if it can predict 75% of the training data accuratly.

## Results

### Data Preprocesing
Below are the variable included and excluded from this model. 

Features | Target | Removed 
------------ | ------------- | -------------
APPLICATION_TYPE | IS_SUCCESSFUL | EIN
AFFILIATION |  | NAME
CLASSIFICATION |  | 
USE_CASE |  | 
ORGANIZATION |  | 
STATUS |  | 
SPECIAL_CONSIDERATIONS |  | 
ASK_AMT |  | 
INCOME_AMT |  | 

### Compiling, Training, and Evaluating the Model

Model includes: 
* neurons: 34
* layers: 2
* activation functions: gelu, tanh

* This model achieved 73% accuracy, 2% less than the target 75%. To try and increase performance, I removed the SPECIAL_CONSIDERATIONS feature which reduced the accuracy rate so that was added back into the model. Other options tried that did not affect the accuracy rate were removing the INCOME_AMT feature, increasing the amount of nodes in the hidden layers, tyring different activation functions like gelu and softsign. 



