# Tableau project:
# Overview
- As the new lead analyst for the New York Citi Bike program, I am responsible for overseeing the largest bike-sharing program in the United States. In this role, I am expected to generate regular reports for city officials looking to publicize and improve the city program.
Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike Data webpage.

  
# Objective
- The objective of this project is to analyze the available City Bike program data and identify user trend and identify areas of opportunities to help improve the city program.
# Analysis
- Bike Station Popularity:
  - Newport Pkwy & Liberty Light Rail bike stations are the top 2 locations for bike rentals.
  - Roughly 800 trips took place per station during October and November of 2020.
- Rideship Trend:
  - Female users take up the majority of city bike rentals and accounts for nearly half the total trip duration
  - Male users tend to be evenly split when comes to customers and subscribers; whereas female users are 4 ~ 6 times more likely to maintain a subscription(habit) of using the shared bikes.
  - Therefore, femal bike users appear to be the target audience of the city bikes. Meanwhile, male users can be further assessed as potential avenues for future marketing or expanding our user base.
  - Usertype Market Trend: Additional, as the winter months arrive, bike usage dropped rapidly for both customers and subscribers.
    - If additional weather data was available, analysis can also be conducted to understand the impact of temperature on the bike-sharing program.  
- Program Maintenance Considerations
  - Bike IDs 44258, 45350, 46532 are 3 of the top 10 bikes utilized in the bike-sharing program. Due to a variety of factors such as location, bike placement, bike condition, etc. these bikes may require more frequent care and maintenance to ensure performance.

# Limitation
- Due to the data size limitation within Tableau, this analysis contains only two months of city bike program data from 2020.
- If further data analysis was allowed, there could be clearer findings on the popular months of the city bike program and whether gender and usertype trends appear to shift throughout the year.
# References
- Data Background: https://citibikenyc.com/system-data
- Data Source: https://s3.amazonaws.com/tripdata/index.html
# Data Fields:
  - Ride ID
  - Rideable type
  - Started at
  - Ended at
  - Start station name
  - Start station ID
  - End station name
  - End station ID
  - Start latitude
  - Start longitude
  - End latitude
  - End Longitude
  - Member or casual ride
  - Data format previously:
  - Trip Duration (seconds)
  - Start Time and Date
  - Stop Time and Date
  - Start Station Name
  - End Station Name
  - Station ID
  - Station Lat/Long
  - Bike ID
  - User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
  - Gender (Zero=unknown; 1=male; 2=female)
  - Year of Birth
