# Neural Network Charity Analysis

## Overview
The purpose of this is to create a binary classifier that is able to predict whether applicants will be successful if funded by Alphabet Soup. Machine learning and neural networks are used to accomplish this task.

## Results
#### Data Reprocessing:
- The target of the model is the "IS_SUCCESSFUL" column.
- Features of our model are all columns except for the "EIN" and "NAME" column, which should be removed.

#### Compiling, Training, and Evaluating the Model
- The neural network model had two hidden layers with 8 and 5 neurons respectively. The activation functions used were ReLu and sigmoid.
- The accuracy was 73.3% and I was unable to achieve the target model performance.
- For my first attempt at optimization, I looked at the "ASK_AMT" values and created bins for the values. The accuracy was below 75% and I was unable to achieve the target model performance. For my third attempt I increased the number of hidden layers and neurons, but was unable to achive the target model. For my last optimization attempt, I changed the activation functions to tanh, but was unable to achieve the target model.

## Summary
The deep learning model did not achieve the target model of 75%. A different model such as decision trees could possiblily solve this problem. Decision trees would be a a good alternative model because its a binary classifier, which is our goal.
