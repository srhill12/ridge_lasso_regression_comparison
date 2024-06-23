# Ridge and Lasso Regression

## Intro

I am going to implement ridge regression on housing data and compare the results to a prior linear regression. Then, I will implement lasso regression to examine which features may be unnecessary to the model.

## Steps

1. Perform ridge regression on the real estate dataset. The target variable in the dataset is the house price of the unit area.

    * split the data into training and testing sets.

    * standardize the data.

    * Use an initial alpha value of 1.

    * Create a ridge regression model and assess its MSE.

    * Use `RidgeCV` to optimize for alpha. Use the following alpha values: 0.001, 0.01, 0.1, 1, and 10. Which of these is the best?

2. Next, create a linear regression model and compare its MSE with that of the ridge regression model. Which has a lower MSE?

3. Then, create a lasso regression model. 

    * Use the [documentation](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html) to train the model on the data. Use an alpha value of 1.

4. Assess its MSE.

## Reference

UCI Machine Learning Repository. 2018. *Real estate valuation data set* [Dataset]. Available: https://archive.ics.uci.edu/dataset/477/real+estate+valuation+data+set [2023, October 17]. ([CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode))
