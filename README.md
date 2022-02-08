# Charity Analysis - Neural Networks

## Overview
I have been tasked with helping Alphabet Soup - a philanthropic foundation dedicated to improving the environment, well-being, and unification through contributions totalling more than $10 billion - to vet potential organizations to ensure proper use of donated funds. This analysis utilizes neural networks to predict the success of Alphabet Soup's donations.

## Results
#### Data Preprocessing
The target variable for this data set, was the success variable, or the indicator of whether or not the funds were used effectively. Features included the following:
    - application type
    - affiliated industry sector
    - government organization classification
    - use case for funding
    - organization type
    - active status
    - income classification
    - special considerations
    - ask amount

EIN and name were removed from the analysis as non-beneficial.

#### Compiling, Training & Evaluating Model
The goal of this analysis was to reach an accuracy score of >0.75. Unfortunately, I was not able to achieve that goal, but I sure did hover around 0.73 for nearly all my models. To attempt to reach that goal, I did four models in total: two layers (relu, leaky relu + relu, relu + tanh), three layers (relu). The activation models and nodes of each layer were altered multiple times, all hovering around the same accuracy score with the relu + tanh model performing the worst. I also removed a number of combination of columns as well.

![results](https://user-images.githubusercontent.com/90879979/152911612-21793667-9e55-40e4-8d7d-dfb3e4ce4a26.png)

## Summary
Overall, the model was moderately successful with a mostly-consistent accuracy score of 0.73. It was very frustrating, though, to do loads of trail and error and with noticeable differences only noticed when negative.  Nonetheless, this model could still be improved through further trial and error. Noticeable improvement may come through a considerable reduction or binning of columns, as well as through more quantitative ovservations of each company.
