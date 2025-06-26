# California-House-Prices-Prediction
Objective is to predict the median house value in a given district based on the values of the other features

Problem Statement
The file housing.csv contains data on median house prices in California districts, derived from
the 1990 census data. The data set contains 20,640 rows, one row per district (house block).
Each row contains the following features:
• longitude: how far west a house is; a higher value is farther west.
• latitude: how far north a house is; a higher value is farther north.
• housing_median_age: median age of a house within the block; a lower number is a
newer building.
• total_rooms: total number of rooms within the block.
• total_bedrooms: total number of bedrooms within the block.
• population: total number of people residing within the block.
• households: total number of households (a group of people residing within a home
unit) within the block.
• median_income: median income for households within the block (measured in tens of
thousands of US dollars).
• median_house_value: median house value for households within the block (measured
in US dollars).
• ocean_proximity: location of the house with respect to the ocean. Can have one of
the following values: NEAR BAY, NEAR OCEAN, <1H OCEAN, INLAND, ISLAND.
The objective in this data set is to predict the median house value in a given district based
on the values of the other features.
1. Explore the data set and display summary statistics of the data. What can you learn
from it on the data?
2. Compute the correlation between each feature and the target median_house_value.
Which features have strong correlation with the target?
3. Which actions do you need to take in order to prepare the data set for the learning
algorithm? Identify at least four such actions.
4. Preprocess the data set using the techniques discussed in class (e.g., imputation of
missing values, discretization). Show a sample of the data set before and after the
preprocessing.
5. Extract at least two new features from the data set that have strong correlation with
the target feature.
6. Run linear regression on the transformed data set. Use 80% of the data set as your
training set and 20% as your test set. Compute RMSE and R2 score both on the
training and the test sets.
7. Does adding regularization improve the results? If yes, which value of λ provides the
best R2 score on the test set? If no, what is the reason for it?
8. Now replace linear regression with DecisionTreeRegressor (in sklearn.tree). What
is the R2 score on the training and test this time? Which phenomenon is observed here?
