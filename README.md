# python_statistics_practice

## Lesson 1
This time, let's examine a dataset of video games that have sold over 100,000 copies.    

**Tasks**    
1. The first step is to load the data and make sure that everything was read correctly: look at the columns, size, the presence of missing values (if any, delete). Also explore the types of variables.   
2. Plot the distribution of the number of games released by year and print the descriptive characteristics of the Year variable.   
3. What platforms have the most releases happened on?    
4. Which Publisher games are most frequently featured in the dataset?    
5. Which region has the highest median sales of Nintendo games? (Regions: NA, EU, JP, Other)    
6. View the sales of Nintendo games in Japan by genre. Look at the median, mean, interquartile range.    
7. Visualize the dynamics of changes in the volume of world sales (Global_Sales) by year for Nintendo games of the following genres: Fighting, Simulation, Platform, Racing, Sports. At what points in time have the most Sports games been sold?    

## Lesson 2    
In this mini-project, we will calculate several product metrics and see what distributions can occur in practice.    

**Tasks**    
1. Load the data, check the number of cases and columns, data types, missing values, what unique values are encountered.    
2. Plot the distribution of the number of impressions (Impressions) for each ad by logarithm the values.    
3. Create a new column with CTR. Look at descriptive statistics and distribution.    
4. Analyze CTR by ad campaign.    
5. Calculate your ad's cost-per-click (CPC). Examine the values obtained using measures of the central trend and measures of variability.    
6. Visualize CPCs disaggregated by gender of users who were shown ads.    
7. Calculate the conversion from click to purchase.    

## Lesson 3    
Imagine that you are an analyst for a bike rental company. A colleague from the London office sent you data for two years: from January 4, 2015 to January 3, 2017. You will have to study the dynamics of the number of leases, the connection with weather conditions and weekends, and also explain several anomalies on the graph.    

**Tasks**  
1. Load the data, check the number of cases and columns, and check for gaps. Make sure the data types were read correctly. If necessary, cast the variables to the required types.     
2. Build a schedule for the number of trips by date and time.    
3. Convert the data and count the number of trips by day. Visualize the result.    
4. Use the aggregated data by day and calculate a moving average with window 3. For your answer, give the number of leases obtained for 2015-07-09, rounded to the nearest integer.    
5. Calculate the difference between the observed and the values calculated using the moving average. Next, find the standard deviation.    
6. Determine the boundaries of the 99% confidence interval, add this information to the dataframe.    
7. Examine abnormally high values and indicate the day on which the number of rentals was highest. Find the cause of the anomaly.    
8. Examine abnormally low values, find the day with the fewest rentals. Find the cause of the anomaly.     

 # Lesson 4    
Now is the time to do your first A / B test.    

**Exercise**    
Imagine working as an analyst for a very large pizza delivery company on a courier app (yes, they usually have a courier app and a separate consumer app).    
You have several restaurants in different parts of the city and a whole staff of couriers. But there is one problem - by the evening, the delivery speed drops due to the fact that couriers go home after a working day, and the number of orders is only growing. This leads to the fact that at the time of the shift change, our delivery is very much sagging in efficiency.    

Our data scientists have come up with a new algorithm that allows couriers to schedule their last orders before the end of the working day so that their delivery route matches the route to their home. That is, for couriers to deliver their last orders for the day, as it were, "on the way" home.    

Together with your team, you decided to roll the A / B test into two equal groups of couriers. Some couriers use the old algorithm without the "along the way" option, others see this option in their application and can choose it. Your task is to analyze the experiment data and help the business make a decision on rolling out the new feature to all couriers.   

# Lesson 5    
You are working in a food delivery app. A colleague came to you with the results of two tests:    

* The first tested the resolution of photos of dishes in the app: users were shown either rectangular or new squared    
* In the second: the order button was updated, and some users saw the old version, and some saw the new one    

A colleague came to you with a request: he looked at the graphs and suggested that there might be differences among the groups. Your task is to help him test hypotheses, draw appropriate conclusions based on statistical tests, and make decisions.    

**Tasks:**    
1. Choose the method that is supposed to work in the first question.    
2. Check if the variances within the groups are homogeneous.    
3. Test for normal distribution.    
4. Compare the averages in the groups presented.    
5. Use Tukey's test and determine which groups are statistically significant differences.    
6. Make a decision: what shape of images will we need to use in thr app?     
7. Choose a method for the second test.    
8. Visualize the distribution of events for the control and test groups.    
9. Look at the descriptive statistics for events by group and by user segment.    
10.Choose a formula for the model, conduct a test.    
