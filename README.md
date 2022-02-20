# MechaCar_Statistical_Analysis
Using R to analyze and create data visualizations of vehicle performance from datasets. 

## Linear Regression to Predict MPG
![Linear Regression](https://github.com/ChicletKeyboard/MechaCar_Statistical_Analysis/blob/090a2adc304d0392868fb0153926c2f7c5eb5d6b/Resources/linear_regression.PNG)

3 Key Takeaways:
* Non-random variable variance is usually 0. With this, we can say that the intercept, vehicle length, and ground clearance coeeficients from the regression analysis provide a non-random amount of variance to the mpg values generated.
* At a significance level of 0.05, we are able to reject the null hypothesis because of the extremely small p-value. The null hypothesis of a linear regression states that the slope (β1) is equal to 0. However, if we reject the null hypthesis, we're stating that alternative (β1 ≠ 0) is true. Thus, proving that the slope is not 0.
* Multiple R-squared increases as more variables are passed through the regression. However, adjusted R-squared controls against this increase, and adds penalties for the number of predictors in the model, thus making it a more accurate predictor of how effective the linear model is. An adjusted R-square of 0.6825 concludes that this linear model predicts the mpg of MechaCar prototypes relatively well.

# Summary Statistics on Suspension Coils
## Total Summary Table
<p align="center">
<img src = "https://github.com/ChicletKeyboard/MechaCar_Statistical_Analysis/blob/4e0f473cb4b9b3764f14faad423e26fce31e866f/Resources/total_summary_table.PNG" width="410" height="70"/>
</p>

## Lot Summary Table
<p align="center">
  <img src = "https://github.com/ChicletKeyboard/MechaCar_Statistical_Analysis/blob/4e0f473cb4b9b3764f14faad423e26fce31e866f/Resources/lot_summary_table.PNG" width="500" height="110"/>
</p>  

The overall variance for the entire dataset indicates that the current manufacturing data meets the 100 pounds per square inch variance limitation. However, when separated into three lots, the third lot demonstrates a much higher variance. Because the lots are chosen randomly, there is a possiblity that a third of the lot does not meet the necessary suspension coils requirement.


## T-Test on Suspension Coils
### T-Test on Entire Lot
<p align="center">
<img src="https://github.com/ChicletKeyboard/MechaCar_Statistical_Analysis/blob/4e0f473cb4b9b3764f14faad423e26fce31e866f/Resources/t-test.PNG">
</p>
At a significance level of 0.05, we fail to reject the null hypothesis since the p-value equals 0.06. Therefore, we cannot reject the fact that the sample mean may be equivalent to the true population mean. Another feature to note is the narrow confidence interval. Although a narrower confidence interval implies that there is a smaller chance of obtaining an observation within that interval, it provides greater accuracy than a wider interval.
