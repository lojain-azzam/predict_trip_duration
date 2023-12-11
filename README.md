# predict_trip_duration
Statistical  assignment, you practice inferential statistics using python. We would like to predict trip duration from a location to another using a taxi. 


Use the following dataset and write the following python functions.

 https://data.cityofnewyork.us/Transportation/2019-High-Volume-FHV-Trip-Records/4p5c-cbgn/data 
 
1-write a function that takes a data frame and computes the trip duration using the difference between pickup_datetime and dropoff_datetime. The new column is added to the data frame and the result data frame is returned from the function

2-write a function that takes a data frame and adds to it the hour of the day and the day of the week from the field pickup_datetime. The new data frame is returned from the function.

3-write a function that computes a new data frame called predictions where the index is
PULocationID/DOLocationID/day of the week/hour and has two columns. the first is the mean trip duration and the second column is the margin of error using 95% confidence interval. The mean is computed for all trip durations for the same PULocationID/DOLocationID/day of the week/hour. The new data frame is returned from the function.

4-write a function that read the data file and calls the three functions to finally generate the data frame that is called predictions

#Rubric for the assignment:

-the function definition matches the requirements from input/out/ and functionality

-the code is documented

-the variable naming and function naming are meaningful

-you have to use scipy to compute the t or z scores

-ou should not program functionality that is already exists in a Python package. Don't re-invent the wheel. !!
