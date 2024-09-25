# CitiBike
What is Citibike?
Citi Bike is a privately owned public bicycle sharing system serving the New York City boroughs of the Bronx, Brooklyn, Manhattan, and Queens, as well as Jersey City and Hoboken, New Jersey. Named after lead sponsor Citigroup, it was operated by Motivate (formerly Alta Bicycle Share), with former Metropolitan Transportation Authority CEO Jay Walder as chief executive until September 30, 2018, when the company was acquired by Lyft. The system's bikes and stations use technology from Lyft.

Why Citibike is popualar?
Eco-system, reduce the CO2 emissions

System Data can be found in Citibike System Data(https://citibikenyc.com/system-data) 
Where do Citi Bikers ride? When do they ride? How far do they go? Which stations are most popular? What days of the week are most rides taken on? We've heard all of these questions and more from you, and we're happy to provide the data to help you discover the answers to these questions and more. We invite developers, engineers, statisticians, artists, academics and other interested members of the public to use the data we provide for analysis, development, visualization and whatever else moves you.

# Data Cleaning and Transformation
Step 1: Selecting and Downloading the Data
Based on the criteria, here are the detailed steps for choosing the right data files:
1) Avoid Older Data: Data from 2013-2015 might have outdated formats and could be inconsistent with newer data structures.
2) Choose Recent Data: Select data from 2018-2019 as they are more recent and likely to have consistent data structures. This will help avoid compatibility issues.
3) Download 2018-citibike-tripdata.zip folder. These files provide a good range of recent data without exceeding the 1GB limit per file.
4) Extract the Files: Unzip the downloaded files and ensure you have consistent columns across the CSVs.

Step 2: Preparing the Data
1) Check Data Consistency: Open the CSV files in Excel or any text editor and ensure columns like "start time," "end time," "station ID," and "user type" are present and consistent.
2) Clean the Data:
Remove unnecessary columns that won’t be used in your analysis, such as station name (if you have ID) or redundant information.
Handle missing or incorrect values. For example, filter out trips with impossible durations or station IDs that don’t exist.


# Tableau
What is Tableau?

Why Tableau good to use?
Provide interactive information on the visualization
freindly for people who is not major in data, aka for the public or everyone

MyFirstViz link[https://public.tableau.com/app/profile/freya.huang/viz/MyFirstViz_17270175292750/CitiBikeStory]


Visualization Analysis:
Two most popular and busiest stations of Top 5 stations using in US are Hoboken Terminal - River St & Hudson Pl and Grove St PATH.
Hoboken Terminal - River St & Hudson Pl in Hoboken (07030) is identified as the most popular station with total trips of 12,029, while Grove St PATH in Jersey City (07302) has the second most popular station, of which the total strips is 11,773 from period June to August 2024. 
As we can see from the popularity map version, the Hoboken Terminal station is closed to the Hoboken Terminal transportation and the Harbour. And the Grove St is next to the International Finance Center. The popualations or the important economic and tuorism spots can affect the usage of the bike stations. Citizens or employees may choose the nearest station to hire the bike for daily on-off works. Hoboken Teminal is one of the largest Interchange Transport Station in Hoboken region, at the same time, the harbour and beautiful seaview nearby.
