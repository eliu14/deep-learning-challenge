# Report on Neural Network Model

## Overview
The purpose of this analysis is to help the nonprofit foundation Alphabet Soup to select the applicants for funding with the best chance of success in their ventures. 
## Results
### Data Processing
* The target variable for our model is "IS_SUCCESSFUL".
* The variables that are features of the model are the following: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
* The variables EIN and NAME should be removed from the input data.
### Compiling, Training, and Evaluation of the Model
* I decided on using different numbers of neurons for the 6 layers. The hidden layers used relu as the activation function. The output layer used sigmoid as the activation function. These choices are made after using keras-tuner.
* No, I was not able to achieve the target model performance.
* I equalized the number of neurons for each hidden layer
## Summary
The results of the best model include:
* Accuracy: 73.27%
* Loss: 0.5643
* 
