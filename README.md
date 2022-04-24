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
2. However, when we include all the variables that we have and fine-tuned our models, the accuracy increases dramatically. 
3. We feel that suicide consist of complex interplay between some variables, that individually does not amount to suicide, just like the swiss cheese model
4. Our best models can achieve an accuracy score of 0.85, which is a great model performance score in predicting suicide rates.
5. However, there must be something else that explains suicide. Therefore, the models can still be improved given more data and variables to work with
6. We believe that this “something else” is the microscopic factor that varies from every individual. Our model only take into account macroscopic factor of a country, but fail to consider the uniqueness of each Individual.
7. It is important to do Scaling, for example using MinMaxScaler() and Hyperparameter Tuning, for example using GridSearchCV() for some regression models.
8. Gradient Boosting Regressor is the best model to predict suicide rates that can achieve 0.85 score, while Multiple Linear Regression is the least accurate in predicting suicide rates.


## What did we learn from this project?
1. Merging Two datasets that have imabalanced number of rows and find the common subset for both datasets
2. Scaling the dataset to achieve better machine learning result, for example MinMaxScaler()
3. Grid Search Cross-Validation to select the best hyperparameters for a machine learning model
4. Feature Importance and Permutation Importance to rank the “importance” of features in a regression model
5. K Nearest Neighbors Regressor
6. Random Forest Regressor
7. Gradient Boosting Regressor
8. Voting Regressor

## References

1. https://www.kaggle.com/code/lmorgan95/r-suicide-rates-in-depth-stats-insights
2. https://towardsdatascience.com/the-suicide-crisis-in-data-7025f8551ca8
3. https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html
4. https://www.analyticsvidhya.com/blog/2018/08/k-nearest-neighbor-introduction-regression-python/
5. https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
6. https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html
7. https://vitalflux.com/gradient-boosting-regression-python-examples/
8. https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.VotingRegressor.html
9. https://scikit-learn.org/stable/auto_examples/ensemble/plot_voting_regressor.html#sphx-glr-auto-examples-ensemble-plot-voting-regressor-py



