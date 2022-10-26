# UMD Alumni Association Data Challenge

##### The UMD Alumni Association, a group comprising students and alumni of the university, inspiring lifelong connections with a global network of alumni, is eager to increase the attendance of first-time attendees and major donors (people who make $50000 or more donations) to their events.

## Business Problem:
The Alumni Association wants to understand what drives first-time attendees and the prospect of attendees making a major gift to the university. The association wants to use this information to increase engagement in existing and upcoming events.

## Business Objective: 
To find out the correlations in events that are successful in attracting first-time attendees and major gift prospects using a data-driven approach.

## Machine Learning: Regression
Target Variable = Percentage of First Time attendees
For Model 1: We have considered and done one hot encoding for Location Code, Group Code and Event Year. (We chose these categorical variables as the number of unique values was < 50)
For Model 2: We have considered and done one hot encoding for Event Year alone.
For Model 3: We have considered numerical columns alone.

We took 70% of our data for training and 30% for testing. We applied Linear and Non-Linear models(KNN Regressor and Random Forest Regressor).Finally, we optimized Non-Linear Models using Randomized Search CV.

The Highest R-Square Obtained for Test: 0.9216
Model: Model 2
Regressor: Random Forest Regressor

## Machine Learning:Clustering
For our dataset, we will check if the years are uniquely distinguishable or not. The data is of 7 years, so if
No. of Clusters < 7: 2 or more sets of Years have very similar data points
No. of Clusters = 7: All the years are Uniquely distinguishable
No. of Clusters > 7: One or more sets of Years has data points which are very different from the rest of the groups.

No. of Years = 7
No. of Clusters formed = 5
This suggests that 2 or more sets of Years have very similar data points


