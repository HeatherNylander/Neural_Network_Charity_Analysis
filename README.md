# Neural Network Charity Analysis

## Overview
Beks has come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.


## Results
#### Data Preprocessing
1. What variable(s) are considered the target(s) for your model?
  - IS_SUCCESSFUL
2. What variable(s) are considered to be the features for your model?
  - Every column with the exception of the two columns we removed: EIN & NAME
3. What variable(s) are neither targets nor features, and should be removed from the input data?
  - EIN & NAME
#### Compiling, Training, and Evaluating the Model
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - First model:2 hidden layers with 100 & 30 nuerons, respectively.
  - Second model: 3 hidden layers with 500, 100, and 10 nuerons, respectively.
2. Were you able to achieve the target model performance?
  - NO
3. What steps did you take to try and increase model performance?
  - changed number of hidden layers, nuerons and increased bin size for "other" application types.


## Summary
I was not able to acheieve an accuracy of 75%. Interestingly, when the sigmoid and tanh activation functions were used, accuracy decreased. My conclusion is that for this dataset, the relu activation function is the most accurate.

##### Model Recommendations
- Try a RandomForest Model
- Get stats on data and drop data based on standard deviation rather than eyeballing the data from a density graph.
