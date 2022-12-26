# MechaCar_Statistical_Analysis
Module 16 Challenge - Statistical Analysis using R

---
## Resources
Operating Platform: Windows 11 Pro [Buy Windows 11 Pro](https://www.microsoft.com/en-us/d/windows-11-pro/dg7gmgf0d8h4?rtc=1) Build 22621</br>
IDE Software: [RStudio](https://posit.co/download/rstudio-desktop/) Build 353 2022.12.0 ()</br>
R Build Version: [Windows R version 4.2.2](https://cran.r-project.org/bin/windows/base/)</br>
R Specific Package: [Tidyverse](https://www.tidyverse.org/)</br>
Resource files: [MechaCar MPG](MechaCar_mpg.csv), [Suspension Coil](Suspension_Coil.csv)

---
## Overview
A fictious company AutosRUs' has created a new prototype car named "MechaCar" and they are running into a few production issues. Using a variety of R scripts and statistical analysis the following will be used to help determine a variety of questions and accomplish the below tasks:
* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots.
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population.
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers.

---
## Linear Regression to Predict MPG

<b>Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?</b></br>
The two coefficients which provided a non-random amount of variance are the Vehicle Length (P-Value 2.60e-12) & Ground Clearance (P-Value 5.21e-08) These two values will have an impact on the MPG (Miles Per Gallon) of the prototype MechaCar. The remaining variables Vehicle Weight (P-Value 0.0776), Spoiler Angle (P-Value 0.3069), & AWD (P-Value 0.1852) do not have a non-random impact to the cars overall MPG. 

<b>Is the slope of the linear model considered to be zero? Why or why not?</b></br>
The slope of this specific model is not less than zero (p-value: 5.35e-11) and is smaller than the standarized value of 5% (.05) 

<b>Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?</b></br>
Additional research needs to be completed in order to determine the key factors as to predicting the MPG of the MechaCar. Below further data is provided to help determine this value. 

---
## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
The current manufacturing for the suspension coils is within the threshold of 100 pounds per square inch (62.29356). There are three different lots which have been manufactured, Lot1 and Lot2 are within the Varience threshold (0.9795918 & 7.4693878 respectuflly) however Lot3 has a Variance (170.2861224) outside the threshold which is cause for greater reseach. This will need to be address and corrected in order to maintain the requested limits of < 100 PSI. 


## T-Tests on Suspension Coils
---
Briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.


## Study Design: MechaCar vs Competition
---
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

In your description, address the following questions:

What metric or metrics are you going to test?

What is the null hypothesis or alternative hypothesis?

What statistical test would you use to test the hypothesis? And why?

What data is needed to run the statistical test?


