# Bot-Bidding-Detection

A project that helped an online advertisement agent detect fake/bot bidding accounts in order to support fair bidding
Steps:
1. Created two new variables-features count per bidder and features’ risk scores per object with more than 560k records 
of bidder account information; applied exploratory data analysis on new variables to determine suspicious patterns
2. Applied Logistic Regression and Naïve Bayes to calculate the probability of being a bot account for each bidder
3. Evaluated performance of two models by log loss and ROC curve; achieved prediction accuracy of 0.81 with logistic regression 
