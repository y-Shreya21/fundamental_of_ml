                          PREDICTION OF HOUSE PRICES USING NEURAL NETWORK
The basken housing Preidiction dataset is wellknown dataset in a Machine Learning often use to regression model.

GOAL: 
The Goal of the case study is to Predict the value of owner occupied home based on various feature 
DATA SET :

The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA. The following describes the dataset columns:

CRIM - per capita crime rate by town
ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS - proportion of non-retail business acres per town.
CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX - nitric oxides concentration (parts per 10 million)
RM - average number of rooms per dwelling
AGE - proportion of owner-occupied units built prior to 1940
DIS - weighted distances to five Boston employment centres
RAD - index of accessibility to radial highways
TAX - full-value property-tax rate per $10,000
PTRATIO - pupil-teacher ratio by town
B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT - % lower status of the population
MEDV - Median value of owner-occupied homes in $1000's



OBJECTIVE:
* the objective is to create a regression model that predicts the home value based certain features .
* Neural networks will aoiled to model these relationship , ultilizing there ability to capture the complex pattwerns and interactions within the dataset.

DATA PRE-PROCESSING:
* Handling missing data .
* Feature Scaleing means doing ina way that 
* train test split  -  diving the dataset in training and testing .
                       70% Training 30% TESTING or 80% Training 20% Testing .
                        K-FOLD CROSS VALIDATION - (In K-Fold Cross Validation, we split the dataset into k number of subsets (known as folds) then we perform training on                            the all the subsets but leave one(k-1) subset for the evaluation of the trained model. In this method, we iterate k times with a different subset                            reserved for testing purpose each time.)


* Trining test set to evaluate the model performance to avoid the overfitting . 
* Feature Engineering is the process of transforming raw data into features that are suitable for machine learning models. In other words, it is the process of selecting, extracting, and transforming the most relevant features from the available data to build more accurate and efficient machine learning models.
NEURAL NETWORK ARTITECTURE :
* Input layer 13 neurons at input layer 
* output layer
* hidden layer
* optimization - 
* lost function -  actaul and predicted value 
* Training and evalutaion. using mean square error & mean absoute error .
* Results
* Model improvents
  extra  info :  size of batch -  no of items are avaiable 



