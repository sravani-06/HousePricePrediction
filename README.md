# HousePricePrediction
**Prediction of House Price using Advanced Regression Techniques**

Our goal is to predict the accurate SalePrice of Houses with given features.
Models are evaluated on the Root-Mean-Squared-Error (RMSE).


**Machine Learning models implemented** :
- Cross Validation: Using 11-fold cross-validation
- GridSearchCV for tuning hyperparamters and doing cv

**Models:**
- Ridge
- Lasso
- Elastic Net
- XGBoost
- Extra tree Regressor
- Bagging Regressor
- Support vector Regressor(SVR)
- Gradient Boositng
- Light GBM
- StackingCV Regressor

To make final predictions, I blended above models predictions together to get more robust predictions.Blending model using best models.
