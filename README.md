# Neural_Network_Charity_Analysis

## Overview of the analysis
### Purpose
The purpose of this project is to use neural networks with TensorFlow to analyze and classify the success of charitable donations.

## Results:

### Data Preprocessing
What variable(s) are considered the target(s) for your model?
- IS_SUCCESSFUL is the target for the model.

What variable(s) are considered to be the features for your model?
- APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features for our model.

What variable(s) are neither targets nor features, and should be removed from the input data?
- EIN & Name are not part of the data and can be 

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
- The model had two hidden layers with 100 nodes in the first and 50 nodes in the second. Both hidden layers used the Relu activation function.
![image](https://user-images.githubusercontent.com/70111980/213945405-1b007bf1-98fb-4e5f-bf51-c4ebfe18b668.png)


Were you able to achieve the target model performance?
- We were close to the target performance, but ulimately were not able to achieve an accuracy of 75% or higher. 
![image](https://user-images.githubusercontent.com/70111980/213945442-33c4c6e6-a480-465a-965d-a7abf64db13d.png)


What steps did you take to try and increase model performance?

- Test 1: Add additional hidden layers

![image](https://user-images.githubusercontent.com/70111980/213945504-cb73e989-bf6a-40f1-bab5-bd6d9af4997d.png)

- Test 2: Add additional nodes within the hidden layers
![image](https://user-images.githubusercontent.com/70111980/213945520-815cee58-2abc-46d4-a094-4bd1f5126afc.png)

- Test 3: Change the activation functions to 'tanh' instead of 'relu'
![image](https://user-images.githubusercontent.com/70111980/213945543-be89669c-ee7b-4174-8b28-4dc447635c35.png)


# Summary:

Overall, with the parameters explored within this model, we were not able to achieve the desired accuracy of 75%. Because this is a binary classification there are other models worth exploring - for instance a random forest classifier may be able to achieve the desired level of accuracy. 
