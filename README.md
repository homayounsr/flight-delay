
# Fligh Delay Insights - Python

# Preprocessing
1. Dealing with null values
2. Dealing with time and turn in to date time pattern

# Goals
1. which airline has the most flights?
2. At which day the delay was higher?
3. At what hour the delay was higher for each airline?
4. Count delays that are less than 5 min, between 5 and 45 min and more than 45 min

## Data
The detailed data was collected through https://www.kaggle.com/code/fabiendaniel/predicting-flight-delays-tutorial/input.
<br> The original dataset contained 581,907,9 rows and 31 columns but after cleaning the data and just selecting the month of january to decrease the amount of data, there were 469,968 rows and 13 columns.

## Which airline has the most flights?
List of all the top 10 highest earners based on the number of days the accommodation is already reserved for the month and the projected revenue.
<img src="./output/output.png" style="max-width: 540px"/>


## At which day the delay was higher?
This plot is showing the count of delay for all airlines based on days. We can see most the majarity of delays happend on monday. But is that mean mos 
<img src="./output/output4.png" style="max-width: 540px"/>


## At what hour the delay was higher for each airline?
This plot is a heatmap that visualizes the count of flight delays for different airlines across various days of the week. I chose to use a heatmap because I had three variables, and I wanted to examine the relationship between these three variables. Therefore, a heatmap was a suitable choice for this analysis. As we can see in the plot, the WN airline had the highest number of delays, and these delays were more frequent on Fridays compared to other days.
<img src="./output/output3.png" style="max-width: 540px"/>

## Count delays that are less than 5 min, between 5 and 45 min and more than 45 min
This plot shows the number of different types of flight delays: those under 5 minutes, those between 5 and 45 minutes, and those over 45 minutes. Regardless of the airline, long delays (over 45 minutes) make up only a small percentage. However, the proportion of delays in these categories varies by airline. For example, SkyWest Airlines has about 30% fewer long delays compared to medium delays (5-45 minutes), whereas Southwest Airlines has four times fewer long delays than medium delays.
<img src="./output/output2.png" style="max-width: 540px"/>


## Conclusion
All the goals for the SQL project were met and we were clearly able to distinguish the top most profitable Airbnb accommodations in Montréal based on their availability in a month. We were able to gather a list of all accommodations with poor ratings for cleanliness that might flare a potential start-up for entrepreneurs who are looking into investing in complementary businesses related to Airbnb. We were able to filter the top most-rated listings for clients who are looking for 5-star accommodations. Also, we were able to add more queries that might possibly help customers in their decision-making.

