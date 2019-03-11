This testing model I am creating is for the prediction of the timeseries data not the forcasting of it. I have removed 
some of the registered values and I am trying to create a model to see how well it predicts those missing data in timeseries
analysis. As this model is not focused on forcasting, I am not going to create extra features like (min, median, max, std of 
each rolling windows of time) using pandas expanding function. 
Rather, I am going to use only Month and Year plus PolynomialFeatures method to generate extra features and use the Linear
regression model. 
