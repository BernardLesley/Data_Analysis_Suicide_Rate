# Predicting Suicide Rates for a Population Group

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) whicg focuses on Suicide Rates from [The WHO Country Suicide Database](https://www.kaggle.com/datasets/russellyates88/suicide-rates-overview-1985-to-2016). For detailed walkthrough, please view the source code in order from:


  
## Contributors

- @syaz1affandi - Data Extraction, Data Cleaning
- @adzikrafi - Exploratory Data Analysis, Data Visualization
- @BernardLesley - Machine Learning (KNN, Linear Regression, Random Forest)

## Problem Definition

- Are we able to predict the suicide rates based on a specific attributes of a population group that we think might explain suicide rates?
- Which model would be the best to predict it?

## Models Used

1. Linear Regression
2. KNN CLustering
3. Random Forest
4. Gradient Boosting Regression
5. Voting Regression

## Conclusion

1. Each variable has low correlation with the suicide rates and thus, we cannot rely on a single variable to predict suicide rates
2. However, when we include all the variables that we have, the accuracy increases dramatically. (0.7 accuracy is achieved)
3. We feel that suicide consist of complex interplay between some variables, that individually does not amount to suicide, just like the swiss cheese model
4. However, the accuracy of 0.75 is still not good enough, and there must be something else that explains suicide.
5. We believe that this “something else” is the microscopic factor that varies from every individual. Our model only take into account macroscopic factor of a country, but fail to consider the uniqueness of each Individual.
6. 


## What did we learn from this project?
1. Merging Two datasets that have imabalanced number of rows and find the common subset for both datasets
2. KNN Clustering to predict numerical values
3. 
4. Voting Regression to take the "average" of multiple prediction model


## References





