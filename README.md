# Project McNulty - Predicting Illegal Drugs Consumption (Classification)

## Contents
You can find the pdf presentation, the code and the original survey data in this repository. 

## Project Approach
All my friends started talking about drugs after the legalization of Marijuana in the state of Illinois. Because of this I decided to work on a project related to this topic. The main idea was to use demographic information, capture by a consumer survey from the Department of Health to predict if somebody consumes illegal drugs or not. This is a binary classification problem, where the possible outcomes are the consumption or not of illegal drugs (excluding Marihuana that's considered legal).


## Project Summary:
- Cleaned Department of Health survey data to predict drugs consumption based on demographics
- Engineered features to maximize information density while reducing complexity, tuned model hyperparameters using grid search, and reduces class imbalances using under-sampling techniques
- A logistic regression model that achieved a 79% of accuracy was the model with the best balance between predictability and complexity
- Built a Flask app where HR could input new hires info and receive a probability of them doing drugs
