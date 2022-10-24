# data_challenge

The file in this repo contains the data challenge. 

Assumptions:
All customers reside in the US
State and region were irrelevant to predicting customer segement
The dataset met the conditions to preform a proportion t-test
Each entry was independent

Code explanation: 
The first thing the program does is visualize the customer density in the US. Then a function is made that visualizes the 
customer density in individual states. Next, region population is compared to profit, and it is through this visualization
that the central region is shown to be underpreforming. The final data visualization shows the aggregate profit over time.

5 models were used to try to predict customer segement based on a variety of features. The dataset was upsampled to create an even distrubution of target values, and the categorical variables were hot encoded. All models had less than 50% preformance, but this may be due to low correlation among the features and customer segement. The best model was a Bernoulli Naive Bayes with an accuracy of 49%.
