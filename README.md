# MechaCar_Statistical_Analysis

## Overview of Analysis

The MechaCar is the newest prototype developed by AutoRU. There have been some production issues that are hindering the the manufacturing team's proggress. This analysis aims to provide insights that may help the team figure out what must be improved. In this analysis, a multiple linear regression analysis was performed to identify which variables in the dataset predict the mpg of the MechaCar prototypes. Next, summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots were collected. T-Tests were run to determine if the manufacturing lots are statistically different from the mean population. Finally, a statistical study was designed to compare vehicle performance of the MechaCar vehicles against other manufacturers' vehicles.

- Deliverable 1: Linear Regression to Predict MPG
- Deliverable 2: Summary Statistics on Suspension Coils
- Deliverable 3: T-Tests on Suspension Coils
- Deliverable 4: Design a Study Comparing the MechaCar to the Competition


## Linear Regression to Predict MPG

A multiple linear regression was performed using multiple design specifications, including vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance.

![Deliverable 1](https://user-images.githubusercontent.com/90656004/151676724-bc3213a5-70ec-472e-9617-b2e7d7c867aa.PNG)

Vehicle length and ground clearance provided a non-random amount of variance to the mpg values in the dataset. These metrics have a statistically significant impact on mpg.

The slope of the linear model is **not considered to be zero**. This is due to the p-value of 5.35e-11 being much lower than the 0.05 assumed statistical significance. Thus, there is strong evidence to **reject the null hypothesis**.

This linear model does effectively predict the mpg of MechaCar prototypes because of its r-squared value of 0.7149, which  indicates that this model is 71.49% accurate.

## Summary Statistics on Suspension Coil

Using the MechaCar Suspension_Coil.csv dataset, summary statics tables were generated to show the suspension coil’s PSI continuous variable across all manufacturing lots and the PSI metrics (mean, median, variance, and standard deviation) for Lots 1, 2, and 3. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.

The PSI summary chart for all three manufacturing lots showed that the variance of the suspension coils was **62.29 pounds per square inch**. This does not exceed the 100 pounds per square inch specification.
![Deliverable 2 total_summary](https://user-images.githubusercontent.com/90656004/151676878-465872cd-28d4-4f20-bc4d-ace0e2cdabe4.PNG)

Breaking the manufacturing data down by each lot reveals that only Lot 1 and Lot 2 are within the 100 pounds per square inch requirement, with variances of 0.98 and 7.47 respectively. Lot 3 has a variance of 170.29 indicating that it has a much larger variance in performance and consistency than the others. 
![Deliverable 2 lot_summary](https://user-images.githubusercontent.com/90656004/151676829-40445840-433f-4b63-8f37-c244c7ecbe59.PNG)


## T-Tests on Suspension Coils

T-tests were performed to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch.

![Deliverable 3 sample](https://user-images.githubusercontent.com/90656004/151677125-4abc150f-0757-4a3d-85c8-3cb15aef16de.PNG)

![Deliverable 3 Lot 1](https://user-images.githubusercontent.com/90656004/151677128-72eed3c3-3d74-4b1d-9365-33041db361e7.png)

![Deliverable 3 Lot 2](https://user-images.githubusercontent.com/90656004/151677133-841a4523-77df-4c06-99f2-de1b9076360b.png)

![Deliverable 3 Lot 3](https://user-images.githubusercontent.com/90656004/151677138-3f49d4aa-e10e-42de-ae76-904f794d2425.png)

- Briefly summarize your interpretation and findings for the t-test results

## Study Design: MechaCar vs Competition

- What metric or metrics are you going to test?
- What is the null hypothesis or alternative hypothesis?
- What statistical test would you use to test the hypothesis? And why?
- What data is needed to run the statistical test?
