# berkeley_portfolio
AI/ML portfolio


# Capstone: Which factors lead to an individual's financial well being

I have changed my original problem state for my capstone project. My new problem statement is to determine the primary factors that lead to an individual's financial well being.  I used a data set from the Consumer Financial Protection Bureau to perform this analysis.  The dataset is available at the following link https://www.consumerfinance.gov/data-research/financial-well-being-survey-data/ I have also included the user guide for the dataset within this repo. It is entitled "cfpb_nfwbs-puf-user-guide.pdf".   

Based on my analysis of the data the following factors are the primary indicators to determining an individual's financial well being. 1. Whether or not the individuals feels as if they are making ends meet.  2. How much an individual spend per month on housing with spending less than $300 a month being an indicator that an individual feels more positive about their financial well being. 3. The amount of household income with greater than $150k a year being and indicator that an individual feels more positive about their financial well being.  Not surprisingly, the indicator of whether or not an individual feels as if they are making ends meet was the most significant indicator of their financial well being. The notebook for my analysis is entitled "CFPB_Financial_Well_Being.ipynb" and a link to it can be found here:  https://github.com/etaliafe/berkeley-ml/blob/main/CFPB_Financial_Well_Being.ipynb 

Next Steps & Recommendations
Next steps for this analysis would be to include weighted values within the regression models and to examine other population categories such as the Age 62+ oversample and the Race/ethnicity oversample to determine if the same indicators apply. Also I would recommend using polynomial features on the Financial skills score to determine if that can improve the mean squared error of the regression model I used for my final recommendations.

# Which classifier performs the best between k-nearest neighbors, logistic regression, decision trees, and support vector machines?  

I used accuracy as the metric to compare performance between these different classifiers.  Based on the results of my findings, the decision tree classifier had an accuracy of 0.8944, the logistic regression classifier had an accuracy of 0.8569, the K nearest neighbor classifier had an accuracy of 0.8814, and the SVC had an accuracy of 0.8810.  With these results the decision tree classifier had the highest accuracy with 0.8944 and SVC had the lowest accuracy with 0.8810.

The notebook entitled "assigment_3_notebook.ipynb" (https://github.com/etaliafe/berkeley-ml/blob/main/assignment_3_notebook.ipynb) contains the classifier analysis.  

Next Steps & Recommendations
Next steps for this analysis would be to include time execution time as an additional metric to consider in deciding the best classifier.  Other next steps include performing analyses around overfitting on each classifier to ensure that the models are not overfitting on the data.  I would recommend both of these next steps, to further refine which classifier performs the best against the data set.


# What Drives the price of a car?
The notebook entitled "prompt_II_taliaferro.ipynb" (https://github.com/etaliafe/berkeley-ml/blob/main/prompt_II_taliaferro.ipynb) is an analytis on the different features that determine the price of a car. It contains the analysis and recommendations to used car dealers on how to tune their used car inventory to sell cars at higher prices.

# Customer Coupon Acceptance

Will A Customer Accept a coupon?

The notebook entitled "customer_coupon_acceptance_analysis.ipynb" (https://github.com/etaliafe/berkeley-ml/blob/e011954bfabb790f65caca3f3a2234500b291605/customer_coupon_acceptance_analysis.ipynb) is an analysis to determine what factors will lead to a customer acceptance of a coupon across various coupon types.  For this analysis I looked at two coupon types.  Bar Coupons and Coffee Coupons.  

Bar Coupon Analysis
The initial analysis was a guided analysis that took a look at the factors that led to a customer accepting a coupon to a bar.  For this analysis I looked at factors such as bar visit frequency, temperature, age, etc. to determine the affect on acceptance of bar coupons.  Based on that analyis the most prevailing factor that affected bar coupon acceptance rates was bar visit frequency.  Those individuals who visited a bar more than once a month had a noticeably higher acceptance rate, approx 77%, than the baseline* acceptance rate of approx. 57%. 

Coffee Coupon Analysis
The coffee coupon analysis was an analysis that aimed to solve the problem of determining the most significant factors that that drove a higher acceptance rate for coffee coupons.  For this analysis I looked at several factors that were available within the provided dataset and determined that the most signifiicant factors that led to higher acceptance rates were;

1. Going to the coffee shop more than once a month
2. Being within age groups that are below 26 years old
3. Travelling to get coffee between the late morning (10am) to early afternoon (2pm)
4. Being unemployed or a student
5. The coupon not expiring for at least 24 hours  

Based on my analysis... with these factors applied the coffee coupon acceptance rate approaches 94% which is much higher than the baseline* acceptance rate of around 50%.

*The baseline acceptance rate represents the overall coupon acceptance rate without filtering on specific categories or factors beyond the type of coupon.









