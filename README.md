# MechaCar_Statistical_Analysis
## Study Design: MechaCar vs Competition
MechaCar_Statistical_Analysis
Module 15 Challenge: 
Deliverable 1:
 Linear Regression to Predict MPG (Miles per gallon)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The “Non-Random” variables include: Vehicle weight, spoiler angle & AWD. 
The variables that had the most amount of random variance were “Ground Clearance” and “Vehicle length”.
Is the slope of the linear model considered to be zero? Why or why not?
The slope is not zero because the p-value is less than 0.05.
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Our Multiple R-squared value is 71% (68% Adjuasted) meaning approximately ~71% of the time the model will correctly predict mpgs. Other outside factors may not have been captured in the dataset but they may contribute to the mpg variables of MechaCar prototypes.
 
Deliverable 2:
We calculated Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
Both Lots 1 and Lot 2 are within the allowed specifications having almost identical Median & MEAN however Lot 3 shows the highest amount of variance, exceeding the allowed manufacturers specs.
   
Deliverable 3:
T-Tests on Suspension Coils
Lot 1 and Lot 3 the PSI values are not different from the population mean. 
However, lot 2 the p-value is 0.6072 which means there is evidence that the suspension coil is different from the population mean. All t-tests can be seen below:
Sample test:
 
Lot 1 Test:
 
Lot 2 Test:
 
Lot 3 Test:
 






Deliverable 4:
MechaCar vs Competition
Using the statistical models we created it would be able to analyze production information of MechaCar’s Competition. Having data for vehicles would allow is to compare between MechaCars production and its competition. This data should include information about vehicle production as well as performance information. There are many ways to compare vehicles using similar metrics. The information could be verified to identify vehicle performance including miles per gallon, car weight, and other physical features that relate to performance. Other ways may include horse power and drag. 
Which information to check?
Hypotheses: So that we can determine which may be better we must have a hypothesis. 
The hypothesis may help us answer a question “Does the size of the engine have any influence mpg?”
Null Hypothesis:
It is Very likely that the size of the engine has a correlation to mpg and there will be enough data to check.
Alternate Hypothesis:
There is No strong correlation between the Engine size and mpg. 
There will be sufficient evidence of to reject the null hypothesis.

Testing
We would need to create a few linear regression models and t-tests could 
be used on the vehicle data with a significance level of 0.05%.


