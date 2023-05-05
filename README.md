# Citi_Bike_Analysis

## Background

Congratulations on your new job! As the new lead analyst for the New York Citi Bike program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike Data webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

## [Citi Bike Data Source](https://s3.amazonaws.com/tripdata/index.html)
The analysis contains data for rides in Jersey City rides during the year of 2022

## [Tableau Analysis](https://public.tableau.com/app/profile/victor.abril.sanchez/viz/Book1_16831588491700/JCCitiBikeAnalysis?publish=yes)

### Start Station Charts Filtered By Month
![Image_1]()
The Station map shows all 320 stations, and we can observe a higher bike usage density as you get closer to the pier of Jersey City. This trend could be because that is where most of the light rail and train stations that take you to NY are. We can also see more members than casual bikers toward the southern stations.

The bar charts show the top/bottom 10 Citi bike stations for Jersey City. Some trends can be identified in these charts. Most of the top stations are closer to a train or light rail station. On the other hand, the bottom stations are farther away from a train or light rail station.

Lastly, we can observe on all the charts that there are more bikers with a membership than casual bikers for this dataset. By filtering these charts by each month, we can observe that the number of casual bikers typically increases during summer.

### End Station Charts Filtered By Month
![Image_2]()
The map shows the regular use of bikes by members and casual bikers across Jersey City. We can observe that some bikers have branched out to end their trip in NY. Some conclusions made about the trips ending in NY:
- Some Bikers work in NY and end up taking their bikes with them to the NY train or Ferry
- Since there are only a few trips ending in NY, Some bikers go for a stroll in the city for the weekend

The bar charts show the top/bottom station for all the trips in the dataset. We can observe that most stations in the top 10 are near a train or light rail station. 

Lastly, with the member/casual and months filters, we can observe the following:
- More members than casual bikers.
- There are more rides during the summer. 

More analysis on the time of the day and day of the week can be conducted to explore these hypotheses further.

### Weekly Analysis of Type of Bike Rides Filtered by Month
![Image_3]()
Based on the pie chart, we can observe that:
- The dataset has more classic bikes than any other type of bike. 
- The dataset a ver few docked bikes
- By filtering through individual months, we can observe that electric bikes increase during the warmer months. However, more is needed to overtake classic bikes. 

After looking at the average bike trip duration per week graph, it is evident that docked bikes are used for significantly more extended periods than any other type of bike. It could be due to the pricing of classic and docked bikes or the fact that electric bikes are faster. More information about the bikes is needed to make a better conclusion.

Lastly, the average trip distance per graph shows:
- Electric bikes typically travel further than other types of bikes. It makes sense that electric bikes travel more since the rider does not have to pedal as much.
- On average, electric and classic bikes are used more on weekends.

### Seasonal Analysis of Type of Bikes
![Image_4]()
Based on the graphs on this dashboard, we can observe that for this subset of the Citi Bike dataset:
- Summer has the most number of bikes used 
- Winter has the least number of bikes used 
- The most popular hours to ride a bike for all the seasons is between 4 PM to 7 PM
- There is a steady peak around 8 AM for each season 

These observations could imply that:
- When the temperature is higher, more riders are willing to go for a bike ride
- Riders typically go for a bike ride after work
- Some riders bike to work, or at least to the train station that takes them to work.
