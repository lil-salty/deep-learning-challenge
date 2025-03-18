# deep-learning-challenge

## Overview of the analysis: 
This challenged aimed to create a machine learning model to be used by a Non Profit organization named Alphabet Soup to help them select applicants for funding with the highest likelyhood of success for their ventures. 

## Results: 

### Data Preprocessing
- The variable for the target of this model: IS_SUCCESSFUL
- The variables for the features of this model: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMOUNT, SPECIAL_CONSIDERATIONS, ASK_AMOUNT
- The variables removed from the input data of this model: EIN, NAME


### Compiling, Training, and Evaluating the Model
- This model initilially utilized two hidden layers of 80 and 30 neurons with the activation functions 'relu' and 'tanh'. The output layer contained 1 neuron and used the 'sigmoid' activation function.
- This neural network model had an accuracy of 0.7300 after 100 epochs, 0.02 under the target model performance
![image](https://github.com/user-attachments/assets/e49f03f0-dfbf-4e08-aeee-51bed02c463e)

### Model Optimization 
The following areas were adjusted in an attempt to optimize the model to fufill the target accuracy performance of 0.75:
- Number of hidden layers
- Number of neurons
- Activation functions
- Number of epochs

After adjustments were made the model was able to achieve an improved accuracy performance but unfortunately did not meet the target goal of 0.75 accuracy.
- The optimized model utilizes three hidden layers of 80, 30, and 30 neurons with the activation function 'relu', 'tanh', and 'tanh' respectivly. The output layer contained 1 neuron and uses the 'sigmoid' activation function.
- The optimized neural network model had an accuracy of 0.7317 after 15 epochs.
![image](https://github.com/user-attachments/assets/273cc2cb-873c-4157-b267-b110922a87f6)


## Summary
The overall results of the optimized machine learning model were still slightly under the target accuracy performance. It is recommended that further optimization of the model done before using the model for its venture predictions. 
