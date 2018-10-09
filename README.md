# machine_learning projects
## Boston housing price prediction using desicsion tree.
## Anaysis steps
1. Explore data and observe features
2. Explore goodness of fit using coefficient of determination, R^2(``r2_score`` from ``sklearn.metrics``)
3. Divide data set into training and test set using ``train_test_split`` from ``sklearn.cross_validation``.
4. Analyze model performance with the followings:
    - Learning curve
    - Complexity curve
5. Explore bias and variance tradeoff by understanding of underfitting and overfitting
6. Evaluate model performance:
    - Grid seach and cross validataion using ``DecisionTreeRegressor``, ``GridSearchCV`` from ``sklearn.grid_search``.
    - Fitting a model
    - Make predictions
