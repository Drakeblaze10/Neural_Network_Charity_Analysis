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
- I was not able to reach the target model performance but was not far off with 73%.

## Summary