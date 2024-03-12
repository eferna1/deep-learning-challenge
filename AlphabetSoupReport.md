# Alphabet Soup Report

## Overview: The goal of this project is to use maching learning and neural networks to predict which applicatns will be successful if funded by Alphabet Soup.  

## Results

## Data Processing 
### 
1. What variable(s) are the target(s) for your model?
The target variable is the 'IS_SUCCESSFUL' column from application_df.

2. What variable(s) are the features for your model?
The feature vaiable are every other column from application_df. 

3. What variable(s) should be removed from the input data because they are neither targets nor features?
Removed both 'EIN' and 'NAME' becuase neither column was a target or feature in the dataset.  

## Compiling, Training, and Evaluating the Model
###
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
In the first attempt, I used 8 hiddent_nodes_layer1 and 5 hiddent_nodules_layer2.  

2. Were you able to achieve the target model performance?
No, was unable to achieve 75% model accuracy. 

3. What steps did you take in your attempts to increase model performance?
I added more layers, removed more columns, and added additional hidden nodes.  

## Summary: Overall, the deep learning model was around 73% accurate in predicting the classification. 