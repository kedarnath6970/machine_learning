# machine_learning projects
## Boston housing price prediction using desicsion tree.
## Steps
1. Explore data and observe features
2. Explore goodness of fit using coefficient of determination, R^2(``r2_score`` from ``sklearn.metrics``)
3. Divide data set into training and test set using ``train_test_split`` from ``sklearn.cross_validation``.
4. Analyze model performance with the followings:
    4.1. Learning curve
    4.2. Complexity curve
5. Explore bias and variance tradeoff by understanding of underfitting and overfitting
6. Evaluate model performance:
    6.1. Grid seach and cross Validataion using ``DecisionTreeRegressor``, ``GridSearchCV`` from ``sklearn.grid_search``.
    6.2. Fitting a model
    6.3. Make predictions
