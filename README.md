# SurpriseHousing
Regression(Lasso and Ridge) model using regularization.

Steps used in this are :-

1.Installing Required Libraries       
2.Import and Inspect dataset              
3.Data Cleaning                      
4.Exploratory Data Analysis                  
5.Data Preparation                   
6.Building ML Model                      

**Ridge Regression :-**  
Ridge Regression, also known as L2 regularization, is an extension to linear Regression that introduces a regularization term to reduce model complexity and help prevent overfitting.  
Ridge Regression helps minimize the sum of the squared residuals and the parameters’ squared values scaled by a factor (lambda or α). This regularization term, λ, controls the strength of the constraint on the coefficients and acts as a tuning parameter.   
Performs L2 regularization, i.e., adds penalty equivalent to the square of the magnitude of coefficients  
Minimization objective = LS Obj + α * (sum of square of coefficients)  

**Lasso Regression :-**  
Lasso (Least Absolute Shrinkage and Selection Operator) Regression is another regularization technique that prevents overfitting in linear Regression models. 
Like Ridge Regression, Lasso Regression adds a regularization term to the linear Regression objective function.  
The difference lies in the loss function used – Lasso Regression uses L1 regularization, which aims to minimize the sum of the absolute values of coefficients multiplied by penalty factor λ.  
Performs L1 regularization, i.e., adds penalty equivalent to the absolute value of the magnitude of coefficients.    
Minimization objective = LS Obj + α * (sum of the absolute value of coefficients)   
Unlike Ridge Regression, Lasso Regression can force coefficients of less significant features to be exactly zero.As a result, Lasso Regression performs both regularization and feature selection simultaneously.  
**Note :-**   
The Dataset is also present in this repository.Please check
