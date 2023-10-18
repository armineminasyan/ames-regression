### Description

This repository contains a Python Jupyter notebook explaining how to implement some regression models.
We apply the models to the Ames Housing dataset, a classical set for advanced regression tasks.

We try the following models:
* **Multiple Linear Regression** with PCA and target quantile transformation
* **LASSO Regression** with target quantile transformation
* **AdaBoost**
* **XGBoost**
* **CatBoost**
* A **Stacked Regressor** combining all the models above, with a CatBoost final estimator

We also build complete pipeline that include automatic data imputation, scaling, and interfacing with Pandas dataframes.

### License

This code is distributed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html#license-text).