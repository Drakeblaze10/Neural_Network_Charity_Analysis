# Neural_Network_Charity_Analysis

## Overview of Analysis
Using Neural Networks, we will be predicting the success of an orginazition who receives funding from Alphabet Soup. The dataset contains over 34,000 organizations.

## Results

# Data Processing
- The target of our model is going to 'IS_SUCCESSFUL' as we would like to see which of the organizations has succeeded and use that as a bases to predict which will succeed.
- The features of the model will be 'APPLICATION_TYPE', 'CLASSIFICATION', and 'INCOME_AMT.'
- Both 'EIN' and 'NAME' were removed from the dataset as they were neither targets nor features.

# Compiling, Training, and Evaluating the Model
- We ended up with three hidden layers. The first had 100 neurons. The second had 50. The third had 10. I stuck with the 'relu' as we are looking for at positive nonlinear input data.
![Compiling](https://github.com/Drakeblaze10/Neural_Network_Charity_Analysis/blob/main/Resources/Neural_model.png)
- I was not able to reach the target model performance but was not far off with 73%.
![Evaluation](https://github.com/Drakeblaze10/Neural_Network_Charity_Analysis/blob/main/Resources/Evaluation.png)

## Summary
The neural network, did an effective job of reducing loss within approx. 30 epochs. I could certainly keep playing with the current model or even changing out the model to improve model perfomance. I am still learning whether support vector or deep learning is better, however I would like to see how SVM handles the perdiction. 