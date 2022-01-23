
In this project, we are going to predict housing prices for the boston housing data. I have used **Linear Regression** and regularized regression methods: **Lasso regression**, **Ridge regression** and **ElasticNet** to predict the housing prices. Polynomial of degree 2 does a good job in predicting housing prices. Best models for each method were selected using extensive gridsearch. All 3 regularized models (**Lasso regression**, **Ridge regression** and **ElasticNet**) show similar accuracy for prediction.

### Final Predictions:

#### Linear Regression:
Train (R2 score) 		:      0.73
Test (R2 score) 		:      0.79 

#### Linear Regression (Polynomial, degree = 2):
Train (R2 score) 		:      0.93
Test  (R2 score) 		:      0.86 

#### Ridge Regression (Polynomial, degree = 2):
Train (R2 score) 		:      0.92
Test  (R2 score) 		:      0.90

#### Lasso Regression (Polynomial, degree = 2):
Train (R2 score) 		:      0.92
Test  (R2 score) 		:      0.90

#### ElasticNet Regression (Polynomial, degree = 2):
Train (R2 score) 		:      0.91
Test  (R2 score) 		:      0.90
