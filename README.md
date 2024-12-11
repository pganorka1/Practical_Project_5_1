# Practical_Project_5_1
Project to analyze real time coupon effectiveness based on customer proximity and customer attributes
Investigating the Bar Coupons
  Conclusions: Drive with following attributes are more likely to accept the bar coupon 1. if they frequently visit bars in general, 2. if they are above 25years of age3. if they do not have kids, 4. Are widowers and 5. are not in the farming fishing occupation
Independent Investigation:
Choosing Restaurant_20_50 for the next case analysis as it has the next lowest acceptance rate
  #####Conclusion
  1.) In investigation of the Categorical input and binary outup(whether driver will use or not use the coupon suggest the following correlation 
  Correlation observed between the drivers decision to use or not use the coupon for Restaurant20_50 (expensive places) and the following predictors 
  a. destination b.weather c. Occupation d.Bar d.Income f. RestaurantLessThan20
  Therefore the above input are good predictors of whether the driver will use or not use the coupon. 
  All other categorical factor/input are deemed as not good predictors of 'Y'
  #2.) In investigating the continous input temperature and has_children it was found that
The p-value for temperature is 2.281e-05, Since p<0.05, null must go, implies which is highly significant, indicating that temperature is a significant predictor of Y. Goodness of fit is 68%
The p-value for temperature is 0.02660, Since p<0.05, null must go, implies which is highly significant, indicating that has_children is a significant predictor of Y. Goodness of fit is 68.4%
Finally these factors need to be further analyzed for the strength of the correlation and the if there is a causal relationship
