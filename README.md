# XGBOOST_ML
---
In the XGBoost library, the booster parameter allows us to choose the type of base learner or model that will be used in the ensemble.

**The booster parameter accepts one of the following values:**

1. gbtree: This is the default option. It indicates that the base learner will be a decision tree.

2. gblinear: This indicates that the base learner will be a linear model.

3. dart: This stands for "Dropout Additive Regression Trees".
 - It's an advanced boosting algorithm that combines aspects of both gradient boosting and dropout regularization.

Choosing the appropriate booster depends on specific dataset and problem.

**NOTE:**

In most cases, the default gbtree booster (decision tree) works well and is widely used. If you have a preference for linear models or want to experiment with more advanced techniques, we can choose gblinear.

---
---
