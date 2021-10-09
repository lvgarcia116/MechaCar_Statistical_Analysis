# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
vehicle_length and ground_clearance provided a non-random amount of variance to the mpg values in the dataset as these variables were less than 0.05, in other words, were statistically significant. The slope is not considered to be zero, also since there is a significant linear relationship between the DV & IV’s, the slope won’t equal 0. This linear model predicts mpg of MechaCar effectively as the overall p-value is less than 0.05, thus is statistically significant in predicting mpg.

<img width="899" alt="Deliverable 1" src="https://user-images.githubusercontent.com/86024512/136638302-f202a004-a0de-47a8-b5d9-cf270884c32f.png">

## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Lot 1 & 2 meet this design specification except lot 3 as this lot has a variance of 170.

<img width="283" alt="Deliverable 2 Total Summary" src="https://user-images.githubusercontent.com/86024512/136638321-a1e9f664-56aa-43ad-a8a7-1d5b2f4aeb05.png">

<img width="441" alt="Deliverable 2 Lot Summary" src="https://user-images.githubusercontent.com/86024512/136638313-a1b6a92c-9df0-4609-a441-f9f98119a46c.png">

## T-Tests on Suspension Coils
The p-value across all manufacturing lots is 0.06028. Since our significance is 0.05 percent, the p-value is above the significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis and the two means are statistically similar.

<img width="578" alt="Screen Shot 2021-10-08 at 9 04 02 PM" src="https://user-images.githubusercontent.com/86024512/136638438-29886d67-16c3-431a-851f-c48694438a9f.png">
<img width="553" alt="Screen Shot 2021-10-08 at 9 04 28 PM" src="https://user-images.githubusercontent.com/86024512/136638441-054ef0d0-bd88-4504-8b5f-213dc691b0e3.png">

## Study Design: MechaCar vs Competition
In an study to compare performance of the MechaCar vehicles against performance of vehicles from other manufacturers this mock study would be reviewing the following three metrics: 
City efficiency, cost, and safety rating.

H0: There is no statistical significant difference on the metrics between MechaCar and the competition

Ha: The is statistical significant difference on the metrics between MecharCar and the competition.

In order to test the hypothesis, a two sample t-test would be used to determine whether the means of two samples are statistically different.

The data needed to run the statistical test is the cost, city efficiency mileage, and safety rating data from 100 vehicles.
