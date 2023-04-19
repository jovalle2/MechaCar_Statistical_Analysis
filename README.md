# MechaCar_Statistical_Analysis
 
## Linear Regression to Predict MPG

The dataset contains mpg results for 50 prototype MechaCars. Each vehicle had different lengths, weight, spoiler angle, ground clearance, mpg, and AWD or not.

![alt text](https://github.com/jovalle2/MechaCar_Statistical_Analysis/blob/main/Images/linear_regression.PNG)

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

For the given dataset it looks like vehicle length, and ground clearance are statistically more likely to provide non-random amounts of variance in this model. These two coefficients have the most impact on miles per gallon on the prototype.

### Is the slope of the linear model considered to be zero? Why or why not?

With a p-value of 5.35e-11 the linear model is not zero since this is lower than the significance level of .05%.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The model has an r-squared value of 0.7149 which is about 71% of all mpg predictions. This model would predict the mpg of MechaCar prototypes effectively.

## Summary Statistics on Suspension Coils

![alt text](https://github.com/jovalle2/MechaCar_Statistical_Analysis/blob/main/Images/total_summary.PNG)

![alt text](https://github.com/jovalle2/MechaCar_Statistical_Analysis/blob/main/Images/lot_summary.PNG)

From the summary variance the suspension coils are not exceeding the 100 PSI as the variance is at 62.29. But looking at the individual lots, lot 3 shows the highest variance at 170.28.


## T-Tests on Suspension Coils
- The first t-test had a p-value of .06. This would not be sufficient evidence to reject the hypothesis.
![alt text](https://github.com/jovalle2/MechaCar_Statistical_Analysis/blob/main/Images/inital_t_test.PNG)

- The t-test for Lot1 had a p-value of 1. This would not be sufficient evidence to reject the hypothesis.
![alt text](https://github.com/jovalle2/MechaCar_Statistical_Analysis/blob/main/Images/t_test_lot1.PNG)

- The t-test for Lot2 had a p-value of 0.60. This would not be sufficient evidence to reject the hypothesis.
![alt text](https://github.com/jovalle2/MechaCar_Statistical_Analysis/blob/main/Images/t_test_lot2.PNG)

- The t-test for Lot3 had a p-value of 0.04. This would be sufficient evidence to reject the hypothesis.
![alt text](https://github.com/jovalle2/MechaCar_Statistical_Analysis/blob/main/Images/t_test_lot3.PNG)

## Study Design: MechaCar vs Competition

Using some more of the basic metrics for vehicles we can put the MechaCar up vs the competition to review if there any significant advantages in going forward with production.

What metric or metrics are you going to test?
 - Cost, city or highway fuel efficiency, maintance cost, and safety rating.

What is the null hypothesis or alternative hypothesis?
 - With these defined metrics there is no statiscal significance between MechaCar and the competition.

What statistical test would you use to test the hypothesis? And why?
 - Using more linear regression test to see the the outcome of the different metrics. Using more regression tests would allow us to see more than just a single variable and account for the total variance observed through all the dependent variables.

What data is needed to run the statistical test?
 - Basic data like cost can be gathered easily. Vehicles would need to be submitted to different tests under the same conditions to gather all the metric data.
