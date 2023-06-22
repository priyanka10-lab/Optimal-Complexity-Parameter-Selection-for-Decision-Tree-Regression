# Optimal-Complexity-Parameter-Selection-for-Decision-Tree-Regression

In this project, the goal is to find the optimal complexity parameter (ccp_alpha) for a DecisionTreeRegressor model using cross-validation. The dataset used is stored in the file "test_sample.csv", which consists of four columns labeled Y, X1, X2, and X3. Column Y represents the dependent variable, while X1, X2, and X3 are the regressor columns.

To find the optimal ccp_alpha, the GridSearchCV function is employed with a 10-fold cross-validation. The grid of ccp_alpha values used ranges from 0.01 to 0.1, with 10 equally spaced intervals. The aim is to minimize the mean squared error (MSE) in cross-validation.

The DecisionTreeRegressor model is then fitted to the data using the optimal complexity parameter determined through the GridSearchCV process. The mean squared error of the fitted model is calculated. The random_state parameter is set to 0 to ensure reproducibility of the results.
