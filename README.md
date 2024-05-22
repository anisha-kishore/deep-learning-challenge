# deep-learning-challenge
# Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

# Analysis
## Overview
The purpose of the analysis is to go through the steps I didwhen I tried to build and optimize a model. I was not able to get to 75% accuracy, but was able to increase my accuracy percentage mainly bu adding another hidden layer but also by other steps which I have detailed below.
## Questions
1. What variables is the target for your model?
   IS_SUCCESSFUL is the target variable of my model.
3. What variables are the features for your model?
    APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION','USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', and 'ASK_AMT' are the feature variables are the features of my model.
5. What variables should be removed from the input data because they are neither targets nor features?
   I am removing 'EIN', 'NAME', and 'STATUS' because there are neither target nor feature variables.
7. How many neurons, layers, and activation functions did you select for your neural network model, and why?
   My first hidden layer had 80 neurons, second hidden layer had 40, and third hidden layer had 20 neurons. I used relu for the hidden layers, but made the activation layer linear.
9. Were you able to achieve the target model performance?
    No, I was able to increase accuracy but was not able to get to 75% accuracy.
11. What steps did you take in your attempts to increase model performance?
    In order to increase model performance, I added another layer, I removed the 'STATUS' column, changed the hidden nodes layers, and decreased the number of epochs.
## Summary
