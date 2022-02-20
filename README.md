# MechaCar_Statistical_Analysis
Using R to analyze and create data visualizations of vehicle performance from datasets. 

## Linear Regression to Predict MPG
![Linear Regression](https://github.com/ChicletKeyboard/MechaCar_Statistical_Analysis/blob/090a2adc304d0392868fb0153926c2f7c5eb5d6b/Resources/linear_regression.PNG)

3 Key Takeaways:
* Non-random variable variance is usually 0. With this, we can say that the intercept, vehicle length, and ground clearance coeeficients from the regression analysis provide a non-random amount of variance to the mpg values generated.
* At a significance level of 0.05, we are able to reject the null hypothesis because of the extremely small p-value. The null hypothesis of a linear regression states that the slope (β1) is equal to 0. However, if we reject the null hypthesis, we're stating that alternative (β1 ≠ 0) is true. Thus, proving that the slope is not 0.
* Multiple R-squared increases as more variables are passed through the regression. However, adjusted R-squared controls against this increase, and adds penalties for the number of predictors in the model, thus making it a more accurate predictor of how effective the linear model is. An adjusted R-square of 0.6825 concludes that this linear model predicts the mpg of MechaCar prototypes relatively well.
