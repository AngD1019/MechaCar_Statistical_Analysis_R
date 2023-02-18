# MechaCar_Statistical_Analysis

This project involves completing the following tasks:
* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots.
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population.
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, write a summary interpretation of the findings.

## Deliverable 1:
### Linear Regression to Predict MPG

<img width="300" alt="Deliverable1 1_Image" src="https://user-images.githubusercontent.com/114960958/219476357-596df8ae-a576-4c0d-8635-6d62d67f190e.png">

#### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The variables that provided a non-random amount of variance to the mpg values in the data set would be vehicle_weight, since the p-value is 0.0776, which is quite low.

#### Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not considered to be zero because the p-value of the linear regression analysis is 5.35e-11, which is much smaller than 0.05 and the absolute value of r is 0.7149. This means that we have sufficient evidence to reject our null hypothesis, and which means that the slope of the linear model is not zero.

#### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

From the data, 3/5 do not have great influence as their p-value is greater than the significance level (0.05), we could say the (we reject the null hypothesis). The ones that could have an impact are: ground clearance and vehicle lenght, with p-values of 5.21e-08and 2.60e-12, respectively (statistically significant to say that fail to reject the null hypothesis).

This shows theres a probability that this values are in fact parameters that greatly affect the mpg and not be due to random chance. The absolute value of r was 0.7149 with p-value (5.35e-11) < 0.05, therefore we could say it represents a strong Pearson's correlation, the slope of the linear model is not zero and this linear model could be used to predict the mpg.

## Summary Statistics on Suspension Coils

write a short summary using screenshots from your total_summary and lot_summary dataframes, and address the following question:
<img width="261" alt="lot_summary_image" src="https://user-images.githubusercontent.com/114960958/219895074-4d4c6abf-7862-4a1c-84e1-ff9f746d1c04.png">

<img width="159" alt="total_summary_image" src="https://user-images.githubusercontent.com/114960958/219894844-4c4ea1e9-e060-4033-a61e-4b882211d761.png">


The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
