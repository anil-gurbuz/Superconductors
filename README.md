# Superconductors
R - Predicting Critical Temperature of Superconductors

Jupyther Notebook document includes the data analysis performed on several substances and their chemical properties. The aim is to build models to predict the critical temperature of substances.
<br></br>
First part is exploratory data analysis. It aims to understand the data and relationships between variables.
<br></br>
Second part explains the development of the models. It explains the decision made to increase the model performance and the evaluation of different options. There are 2 main models. A regression model developed with stepwise feature selection using BIC, Adjusted R^2 and C_p. Also, Ridge(L1) and Lasso(L2) versions are developed for the regression model. Best performing regression model out of these 5 is kept as a benchmark model.
<br></br>
Additionaly, XGBoost model is created after grid-searching for optimum hyperparameter values.
<br></br>
Also, for both XGBoost and Regression models, importance of parameters are assessed to understand factors affecting critical temperature of a superconductor.
<br></br>
Finally, resulting models are compared.
