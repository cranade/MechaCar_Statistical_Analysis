# MechaCar_Statistical_Analysis

## Chandrashekhar G. Ranade

  The goal of this challenge is to see if,  based on the data provided for the AutosRUs’ newest prototype, the MechaCar, what is the relationship between the Miles Per Gallon (MPG) and various variables such as the Length and Weight of the vehicle, Spoiler Angle, Ground Clearance and All Wheel Drive. This to be done using R Programming.



### Deliverable 1: Regression Results

The following table gives the regression results for the MPG as dependent variable, and the other variables mentioned above as explanatory variables in a linear regression estimation.

 ![Chart](https://i.imgur.com/xt5xhoE.png)

 All the explanatory vehicle length and clearance, are positively related (their coefficient being positive and also significantly different for zero at 0.001). It should be pointed that this 0.001 is a very low level of significance, and actually some statisticians (like our team)  will treat that no variable is significantly related to the MPG. Vehicle weight and spoiler angle have turned to be insignificant even at 0.001. We will recommend the AutsRUs team to experiment more on these variables to significantly increase the relationship of these variables with the MPG to boost the sales. More experimentation is needed since the weight is supposed be negatively correlated with the MPG, according to the EPA.

### Deliverable 2: Technical Analysis for Suspension Coil

The summary table shows the following Mean, Median, Variance and Standard Deviation of the data on Suspension Coil.

 ![Chart](https://i.imgur.com/lZ3QLuy.png)

 The mean and median are not much different and also the standard deviation is low, meaning that there are no extreme observations in the data.

 Comparison of three lots in terms of the above parameters shows the following picture:

 ![Chart](https://i.imgur.com/W841SM1.png)

### Deliverable 3

 The statistical significance analysis was done for the grand mean (1500) with the means for each lot and we again found that the means are within the confidence interval of 95% and hence are not statistically different from the overall mean.

 The box plot for the total sample and the three lots also show that there is not much variation in the mean.

 ![Chart](https://i.imgur.com/F9NmueF.png)

 ![Chart](https://i.imgur.com/lZyVW6K.png)

 One Sample Test below confirms that the mean lies within the confidence interval of 95% for the total sample as well as three lots.

 ![Chart](https://i.imgur.com/WTmqCHw.png)


t-test for the three lots also confirms the results


 ![Chart](https://i.imgur.com/yuPcVTD.png)

  ### Conclusion

  Our advice to AutsRUs will be to experiment more about the efficiency related to the weight and length of the vehicle and after reconfirming the above results do aggressive marketing that all lots are fine and the choice will depend on the consumer preference related to the other factors like the look of the vehicles.
