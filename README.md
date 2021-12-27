# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![mecha_car_screenshot](https://user-images.githubusercontent.com/38074766/147437187-72413df2-e166-4b41-aba2-d44320055c4b.png)

The length of the vehicle and ground clearance seems to provide on-random variances to the model.  Therefore the length and ground clearance of the vehicle will have a statistical impact on the mpg of the prototype.  However, the rest of the car: vehicle weight, spoiler angle, and AWD all have a p-value that indicates random variance.

The p-value of 5035e-11 is a lot smaller than our 95% confidence level, therefore allows us to reject our null hypotheisis.

This model has an r-squared value of .7149 wh ich means 71% of all mpg predictions will be based on this chart, thus correctly predicting the mpg of th MechaCar prototypes effectively.




## Summary Statistics on Suspension Coils
![mecha_car_screenshot 2](https://user-images.githubusercontent.com/38074766/147437197-4e8f2810-7e83-4d93-8d44-b1d299cd8d30.png)

![mecha_car_screenshot 3](https://user-images.githubusercontent.com/38074766/147437251-0bd963e4-6472-419d-90e5-8d180d4b31f7.png)

The variance of coils are 62.29 and are within the 100 PSI limit.  However, Lot 3 has a variance of 170.29, which is above the 100 PSI variance limit.

## T-Tests on Suspension Coils
![mecha_car_screenshot 5](https://user-images.githubusercontent.com/38074766/147437269-202a3748-c741-4dc8-a05a-52a4d4096791.png)

With a p-value of 0.06, which is greater than 95% confidence level, there is NOT enough evidence to reject the null hypothesis.  The lot is statistically similar to the population mean of 1500.

For lots 1 and lots 2, we cannot reject the null hypothesis with a p-value of 1 and 0.61 respectively.  

However for lots 3 WE WILL reject the null hypothesis with a p-value of 0.05 which is within the 95% confidence interval, which demonstates that the sample and the population are not similar.

## Study Design: MechaCar vs Competition

Here's what what we need to collect data on the car:

## Metrics to compare to other manufacturers:

Price
MPG
Reviews
Performance
Drive Train


## Hypothesis:

Mecha Car statistically is priced correctly compared to its competitors.
Mecha Car statistically is not priced correctly compared to its competitors.

Since we're testing multiple variables, we will use a Multiple Linear Regression to test our hypothesis.
