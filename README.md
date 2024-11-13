# Analysis of Car Prices

### Summary of Findings

The first part of the notebook cleans and prepares the data for manipulation and modeling. In this section, we use a correlation matrix to find the top coefficients that relate to price, noting features like diesel-utilizing cars, amount of cylinders in the engine, having front-wheel drive, and others. By utilizing the correlation matrix, we have a control to compare
the findings of the model in the next section to.

The second part the notebook utilizes linear regression and Lasso models to score the same features and coefficients. Upon looking at the R2 values of the two models, it was clear that the Lasso model was much more reliable than the Linear Regression model. Finding the top coefficients from the Lasso model, we have fortunately found that the same features are the 
top predictors for price. Among diesel-fueled cars, cylinders, and front-wheel drive, we have found that year is also a crucial determinant in price. 
