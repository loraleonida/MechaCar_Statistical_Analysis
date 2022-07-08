# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The variables that provide a non-random amount of variance to the mpg values are vehicle weight, spoiler angle, and AWD. This is determined by their Pr(>|t|) value. Vehicle weight, spoiler angle, and AWD have probabilities of 0.078, 0.31, and 0.18 respectively- indicating that they are statistically unlikely to provide random amounts of variance to the mpg values.

- Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not considered to be zero because the p-value is 5.35e-11, which is much smaller than the assumed level of significance of 0.05%. Therefore we can reject the null hypothesis, which means the slope of the model is not zero.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
I think this linear model does predict mpg of MechaCar prototypes effectively because the r-squared value is 0.72, meaning that roughly 72% of the variability of mpg is explained using the linear model. The closer the r-squared value is to 1 the stronger the correlation, and the higher the correlation between two variables, the more one variable can predict the value of the other. 

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The variance of all manufacturing lots is 62.29 and therefore meets the design specifications. 

The variance for Lot 1 is 0.97, Lot 2 is 7.47, and Lot 3 is 170.28. Of these three lots, the only lot that the variance does not meet the 100 pounds per square inch design specification is Lot 3. The variance of Lot 1 & 2 falls within the design specification for the suspension coils.


## T-Tests on Suspension Coils

The p-value results of the t-test are as follows:
- All manufacturing lots p-value: 0.06
- Lot 1 p-value: 1.0
- Lot 2 p-value: 0.61
- Lot 3 p-value: 0.04

For all the lots together, and the individual lots 1 and 2, the p-value is above the significance level of 0.05% and therefore we cannot reject the null hypothesis. This indicated the means from these 3 are statistically similar to the population mean of 1,500.
The p-value from lot 3 is below the significance level of 0.05% and therefore we can reject the null hypothesis. This indicates the mean of lot 3 is are statistically different from the population mean of 1,500.


## Study Design: MechaCar vs Competition

In your description, address the following questions:
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?

A statistical study that can quantify how the MechaCar performs against the competition would be a study that compares the MechaCars city and highway fuel efficiency and safety rating with other vehicles in its class.

The alternative hypothesis would be if the MechaCar is a superior performance car, then it will have better fuel efficiency and higher safety ratings than other vehicles in its class. 

The null hypothesis would be if the MechaCar is not a superior performance car, then it does not have better fuel efficiency or higher safety ratings than other vehicles in its class.

The statistical test that would be performed to test the hypothesis would be 

The data needed to run the statistical test would be the city and highway mpg and the safety rating for each vehicle being compared.