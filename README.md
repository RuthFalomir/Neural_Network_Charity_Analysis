# Neural_Network_Charity_Analysis

## Overview of the analysis:
The purpose of this analysis was to create a machine learning model, based on deep learning, that can help this organization predict which projects will make better (and more succesful) use of their donations. The bottom line is, who is gets the money and who doesn't. 

## Results

### Data Preprocessing
- What variable(s) are considered the target(s) for your model?
The variable IS_SUCCESSFUL is our target.

- What variable(s) are considered to be the features for your model?
All variables except for the target variable IS_SUCCESFUL and the identification columns EIM and NAME were considered features. The list is as follows:
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested

- What variable(s) are neither targets nor features, and should be removed from the input data?
As mentioned previously, identification columns EIM and NAME where removed. Furthermore, SPECIAL_CONSIDERATIONS_N was also removed since having both yes and no columns was redundant.

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
Below we present our original model and three further optimization attempts.

### First model
<img width="394" alt="first model" src="https://user-images.githubusercontent.com/88563922/153721950-3f8d7e24-5531-455a-ad15-a6e62736456b.png">

### First optimization attempt
<img width="406" alt="second model" src="https://user-images.githubusercontent.com/88563922/153722002-ce94183f-4378-40ea-9f9b-56d730e0bf74.png">

### Second optimization attempt
<img width="410" alt="third" src="https://user-images.githubusercontent.com/88563922/153722006-4f69c7d1-2d54-412d-af9b-44019cc95fb5.png">

### Third optimization attempt
<img width="400" alt="fourth" src="https://user-images.githubusercontent.com/88563922/153722008-cf20416a-8fa0-4f9a-b897-9df6aee087f6.png">


Were you able to achieve the target model performance?
We weren't able to achive the target model perfomance. However we came close with an accuracy of 0.7262.

What steps did you take to try and increase model performance?
We chose to change the amount of hidden layers, the amount of neurons and also the activation methods. 

## Summary: 
The overall results of the deep learning model didn't reach the goal, however, there are still many optimization alternatives we can try. We recommend trying with higher number of epochs in order to train the model for longer. 
