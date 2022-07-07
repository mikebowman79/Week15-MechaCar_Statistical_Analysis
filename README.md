# Week15-MechaCar_Statistical_Analysis

MechaCar_Statistical_Analysis

The purpose of this analysis is to analyze vehicle production metrics by means of linear regression models and t-tests

Linear Regression Analysis to predict Miles per Gallon (MPG)

![image](https://user-images.githubusercontent.com/101996041/177672574-9fbc5cdd-5a7f-4f29-a2d6-9599222cd021.png)

The following coefficients provide a non-random amount of variance to affect MPG based on the linear regression model: 
-Vehicle Length
-Ground Clearance
-MPG (intercept)

![image](https://user-images.githubusercontent.com/101996041/177672649-37fd053a-eb08-46ff-842e-945c112e58b0.png)
Summary
1.	The slope of the linear model would not be considered zero
2.	The p-value of 5.35e-11 is smaller than the significance level of 0.05
3.	The null hypothesis would be rejected indicating that this is a non-zero slope
4.	The linear model does predict the mpg of the MechaCar effectively; the r-squared value is
0.7149 which would indicate that this model would predict 71% of mpg predictions

Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of all lots of the manufactured coils must not exceed 100 pounds per square inch. Information regarding the coils are as follows:

Total Summary
![image](https://user-images.githubusercontent.com/101996041/177672871-03fb016d-f706-4238-a5c2-44ee7a01317a.png)
1.	As shown above, a summary of all lots of the coils indicates that the variance is 62.29356 which is within design specifications
2.	When Individual lots are shown (below) this indicates that the variance of Lot 1 and Lot 2 are within design specifications but Lot 3 exceeds those specifications with a variance of 170.286.

Individual Lots

![image](https://user-images.githubusercontent.com/101996041/177672944-ae1bada9-68ef-4760-b19b-80c27af93bd8.png)


T-Tests on  Suspension Coils

All Lots: 

![image](https://user-images.githubusercontent.com/101996041/177673055-824add7f-63eb-43fd-9132-c1d116f77f5e.png)


Lot 1: 

The t-test of Lot1 indicates that the PSI of Lot 1 is not statistically different from the population mean as indicated by the p-value of 1.

![image](https://user-images.githubusercontent.com/101996041/177673129-e6574690-4c73-4173-881a-7899b93cc1ad.png)


Lot 2: 
The t-test of Lot1 indicates that the PSI of Lot 2 is not statistically different from the population mean as indicated by the p-value of 0.61.

![image](https://user-images.githubusercontent.com/101996041/177673229-247985ba-5900-4791-a4f6-461fbb7d0ab2.png)


Lot 3: 
The t-test of Lot1 indicates that the PSI of Lot 3 is slightly statistically different from the population mean as indicated by the p-value of 0.042.

![image](https://user-images.githubusercontent.com/101996041/177673284-f17961ad-aed0-4050-8c25-ee0ade0b9561.png)



Study Design: MechaCar vs Competition


In order to compare the MechaCar models to their competition, other metrics might be considered in future statistical analysis.
Based on the car model being studied, other factors might include: 

1.	Towing capacity under normal road conditions
2.	Carrying capacity under normal road conditions
3.	Horsepower under normal road conditions
4.	Off road factors including factors 1-3 above and road tests under different types of terrain.

Null vrs Alternate Hypothesis

1.	Null hypothesis: MechaCar vehicles have similar MPG as compared to competitor vehicles in similar performance conditions
2.	Alternate hypothesis: MechaCar vehicles have better or worse MPG than other competitor vehicles



















