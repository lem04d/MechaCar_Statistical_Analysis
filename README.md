# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![image](https://github.com/lem04d/MechaCar_Statistical_Analysis/blob/main/Module15/linearregression.PNG)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

The variables "vehicle_length" and "ground_clearance" provide a non-random amount of variance to MPG

Is the slope of the linear model considered to be zero? Why or why not?

Based on the summary above, we can see that the p-value for the model was 5.35e-11. The p-value is much smaller than the assumed significance level of 0.05. Therfore there is enough evidence to reject the null hypothesis and we can conclude that the slope is not zero.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

Yes, this linear model predicts the MPG of MechaCar prototyples effectively. The r-squared coefficient is 0.71, showing there is a moderate correlation between the data examined and how it relates to MPG. This means that 71% of the variations in MPG for each vehicle can be attributed to the other variables.


## Summary Statistics on Suspension Coils

The table below is a summary of statistics for the PSI of all of the MechaCars suspension coils. The current manufacturing data meets the design specifications for the lots altogether since the variation does not exceed 100.

![image](https://github.com/lem04d/MechaCar_Statistical_Analysis/blob/main/Module15/total_summary.PNG)



![image](https://github.com/lem04d/MechaCar_Statistical_Analysis/blob/main/Module15/lot_summary.PNG)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The lots in total do not exceed 100 PSI in the variance of the susupension coils but when you break them down by lots, lots 1 and 2 both fall below the 100 PSI in variance at .97 and 7.4 PSI in variance respectivley. However lot 3 shows a large variance of over 170 PSI which indicates that there is a manufacutring issue within this lot. 


## T-Tests on Suspension Coils

Looking at the results of the T-tests from the lots as a whole, we have a p-value of .06 which is above the signifigance level of .05 which indicated that there is no statistical difference between the means of all 3 lots and the presumed PSI of 1500.  We also break down the lots and do a T-test on each of them which confirm that the means of each lot individually are statistically the same as the presumed PSI mean of 1500. 


T-Test

![image](https://github.com/lem04d/MechaCar_Statistical_Analysis/blob/main/Module15/ttest.PNG)

T-Test Lot 1

![image](https://github.com/lem04d/MechaCar_Statistical_Analysis/blob/main/Module15/ttest_lot1.PNG)

T-Test Lot 2

![image](https://github.com/lem04d/MechaCar_Statistical_Analysis/blob/main/Module15/ttest_lot2.PNG)

T-Test Lot 3

![image](https://github.com/lem04d/MechaCar_Statistical_Analysis/blob/main/Module15/ttest_lot3.PNG)


## Study Design: MechaCar vs Competition

Safety ratings are extremely important to car buyers and ensuring that the safety ratings of MechaCar are high compared to the competition would give MechaCar a competitive advantage. 

For the hypothesis, the null hypothesis would be that the safety ratings of MechaCar and the comparable competitors would be equal and there would be no difference in the means. 
The alternate hypothesis would be that there is a difference in the means of the safety ratings. 

The statisitical test used would compare the data from the vehicles crash test data to the best possible outcomes from each test to see which vehicles' means fall closer to that perfect score. MechaCar would want to be both as close to that score as possible as well as being higher in their scores than their competition. 

I would reccommend using crash test data and the ratings provided from MechaCar and the top 5 closest competitors. 
