# Predicting Bike Rentals
by Nicholas Archambault

Many American cities have communal bike sharing stations where you can rent bicycles by the hour or day. Washington, D.C. is one of these cities. The District collects detailed data on the number of bicycles people rent by the hour and day. 

The data was compiled into a file containing 17380 rows, with each row representing the number of bike rentals for a single hour of a single day.

This project attempts to predict the total number of bikes rented in a given hour using a variety of machine learning models.

## Goals
1. Engineer features for suitable use in machine learning analysis.
2. Compare accuracies of linear regression, decision tree, and random forest models.
3. For the most accurate of these model types, investigate the parameter combination that drive error lower.

## Output
A random forest model that minimizes error among the model types tested; visualization of how error is affected by changing parameters within the random forest algorithm.