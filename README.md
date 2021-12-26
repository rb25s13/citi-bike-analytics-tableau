# Citi Bike Analytics - Tableau 

Aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

* [Tableau Public Link](https://public.tableau.com/views/citi-bike-analytics_16359952060010/CitiBikeAnalyticsforJerseyCity?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

### Contents:

        /data - monthly data in csv format
        combined_and_cleaned_csvs.zip - csv files from data cleanup
		data_cleanup.ipynb - code for combining files and cleanup
		
### Analysis:

Station Popularity - There is a clear correlation between the most popular start stations and the end stations. In fact, the top 9 of the two lists are identical.The map is a good representation of the hotspots and perhaps indicate where you are most likely to find a bike. The bar charts show the large difference between the most popular and the least popular stations.

Hourly, Daily & Monthly - Time of day  is an obvious indicator due to the popular 9-5 working schedule of many Americans. There is decent gain during work hours that may indicate people are using them on the job. There is a significant drop off during the evening after rush hour. The weekend does have a slightly higher than average rider count compared to the weekdays. The increases are primarily from casual riders while Saturday is the peak day for total number of riders. The climate seems to be a main influencer to the total number of riders throughout the year. The winter monthshave the clear dip that we previously noted. 

Member Type - The total number of riders is cyclical with the climate. During the winter, the rider count is less than 10% of the rider count in the summer. The rider type is either casual who pays per ride, or a member who pays an annual fee of $179. The two types rise at a similar rate until summer, where the number of member riders  plateaus while the number of casual riders continues to rise. This may be due to more people getting out to enjoy the weather in the summer months.

Station Trips - A majority of the riders do not end their ride at the station they started at. The line graphs show the large difference between the one-way trips and round-trips. My assumption is that the trips are primarily used for a specific destination in mind, rather than a leisure ride. The table matrix shows the counts of the top 10 to and from destinations. The colors make it clear that there are certain stations that do have a higher number of riders returning the bike to the start station. This gives a view that may not be apparent from looking at charts.

Distance & Duration - The line charts below represent a comparison of the average distance and average duration of the trips to the type of rider (member, casual) throughout the year. The average trip duration during the winter months is significantly higher which may be due to the road conditions and climate.  The average trip distance does increase as it gets warmer, indicating that the riders are more willing to be out on the bikes longer.