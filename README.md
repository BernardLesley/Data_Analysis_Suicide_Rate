# Predicting Suicide Rates for a Population Group

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) whicg focuses on Suicide Rates from [The WHO Country Suicide Database](https://www.kaggle.com/datasets/russellyates88/suicide-rates-overview-1985-to-2016). For detailed walkthrough, please view the source code in order from:
1. clean_data.ipynb
2. exploratory data analysis.ipynb
3. machine learning.ipynb
  
## Contributors

- @syaz1affandi - Data Extraction, Data Cleaning
- @adzikrafi - Exploratory Data Analysis, Data Visualization
- @BernardLesley - Machine Learning (KNN Regressor, Linear Regression, Random Forest regressor, etc)

## Problem Definition

- Are we able to predict the suicide rates based on a specific attributes of a population group that we think might explain suicide rates?
- Which model would be the best to predict it?

## Models Used

1. Multiple Linear Regression
2. K Nearest Neighbors Regressor
3. Random Forest regressor
4. Gradient Boosting Regressor
5. Voting Regressor

## Conclusion

1. Each variable has low correlation with the suicide rates and thus, we cannot rely on a single variable to predict suicide rates
2. However, when we include all the variables that we have, the accuracy increases dramatically. (0.7 accuracy is achieved)
3. We feel that suicide consist of complex interplay between some variables, that individually does not amount to suicide, just like the swiss cheese model
4. However, the accuracy of 0.75 is still not good enough, and there must be something else that explains suicide.
5. We believe that this “something else” is the microscopic factor that varies from every individual. Our model only take into account macroscopic factor of a country, but fail to consider the uniqueness of each Individual.
6. It is important to do Scaling, for example using MinMaxScaler() and Hyperparameter Tuning, for example using GridSearchCV() for some regression models.
7. Gradient Boosting Regressor is the best model to predict suicide rates, while Multiple Linear Regression is the least accurate in predicting suicide rates.


## What did we learn from this project?
1. Merging Two datasets that have imabalanced number of rows and find the common subset for both datasets
2. Scaling the dataset to achieve better machine learning result, for example MinMaxScaler()
3. Grid Search Cross-Validation to select the best hyperparameters for a machine learning mode
4. Feature Importance and Permutation Importance to rank the “importance” of features in a model
5. K Nearest Neighbors Regressor
6. Random Forest Regressor
7. Gradient Boosting Regressor
8. Voting Regressor

## References





