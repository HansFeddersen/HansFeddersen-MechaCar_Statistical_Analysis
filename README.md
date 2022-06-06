# MechaCar_Statistical_Analysis

Data Bootcamp Module 15: R


## Linear Regression to Predict MPG.


**Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**
- Two variables, the vehicle length and the ground_clearance.

**Is the slope of the linear model considered to be zero? Why or why not?**
- No, is not considered to be zero, because some independent variables have an effect in some dependent variables. Also the p-value is really low (5.35e-11)

**Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?**
-Yes, because the R-squared value is 0.7149, which means that the model will be effective 71% of the times (we can assume is effective)


![This is an image](https://github.com/HansFeddersen/Election_Analysis/blob/main/Challenge/Resources/More/Total%20_number%20_of_votes.png)

## Summary Statistics on Suspension Coils.

**The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?**

![This is an image](https://github.com/HansFeddersen/Election_Analysis/blob/main/Challenge/Resources/More/Total%20_number%20_of_votes.png)

All lots in total meet the design specification (variance of 62.29). If we look at each lot individually, only lot 1 and 2 meet the design specification (with 0.979 and 7.46 respectively), while lot does not meet the specification (variance of 170.28)
