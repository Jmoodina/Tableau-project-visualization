# Tableau-Project
# 🚴 Overview:
I am excited to assume the role of Lead Analyst for the Citi Bike program in New York, overseeing the largest bike-sharing initiative in the United States. This program, in operation since 2013, has established a robust data collection infrastructure, with monthly updates available on the Citi Bike Data webpage. At your request we will be taking a look at the time period from the months of July-August of 2020 to examine any trends on those summer months. 

## Task:
Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.
1. Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.
• The following are questions you may wish to answer. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!

• How many trips have been recorded in total during the chosen period? 577,703 

• By what percentage has total ridership grown?

• How have the proportions of short-term customers and annual subscribers changed? Fluctuates per day

• What are the peak hours when bikes are used during the summer months? 17-18

• What are the peak hours when bikes are used during the winter months?

• Today, what are the top 10 stations in the city for starting a journey? Based on data, why do you hypothesize these are the top locations?

• Today, what are the top 10 stations in the city for ending a journey? Based on data, why?

• Today, what are the bottom 10 stations in the city for starting a journey? Based on data, why?

• Today, what are the bottom 10 stations in the city for ending a journey? Based on data, why?

• How does the average trip duration change by the type of user? (This may be under "User Type" or "member_casual" depending on the period the data is from).

• What is the average distance in miles for a bike trip?

• Which bikes (by ID) are most likely due for repair or inspection in the timespan?

• How variable is the utilization by bike ID?

2. Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.
3. Create one of the following visualizations for city officials:
• Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.
• Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.
• The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.
4. Create your final presentation:
• Create a Tableau story that brings together the visualizations, requested maps, and dashboards.
• Ensure your presentation is professional, logical, and visually appealing.

# Important
I was unable to submit my workbook as the file is over 100 mb. Here is a link instead: https://public.tableau.com/views/Story4_17033870580770/Story4?:language=en-US&:display_count=n&:origin=viz_share_link

## Story Board 1: User Growth tracking

![Alt text](<Story 1.png>)

First Data visualization is the rate of rider share growth per month over the course of three months.
Second Visual: Rate of growth for subscribers and customers over three months. This visual can be used to justify reasons as to why gaining a specific user type is growing more than the other. 
Third: A quick visual for the total trips taken during these months. If the dataset was larger you can further create comparisons.

## Story Board 2: Station Popularity Dashboard

![Alt text](<Story 2.png>)

Each line graph shows the starting station and the ending station popularity during the day. Through this visualization we can conclude the busiest times for starting and returns are between 17:00 to 18:00 (5-6). This could be due to the roads being heavily congested or the majority of the workforce clocking out. 

On the right is a quick visualizer for each user type and the average total trip duration by each. 

## Story Board 3: Starting Station Mapped Out

![Alt text](<Story 3.png>)

On the left you can see the geolocation of each starting station over the course of the time period.
On the right you can see the most popular stations at the top and the least popular station at the bottom likewise with the ending stations. 

Upon further inspection there seems to be common stations with less popularity and particular stations who are the publics favorites. 

## Story Board 4: Starting Station Mapped Out

![Alt text](<Story 4.png>)

On the left you can see the geolocation of each ending station over the course of the time period.
On the right you can see the most popular stations at the top and the least popular station at the bottom.

Upon further inspection there seems to be common stations with less popularity and particular stations who are the publics favorites similar to the starting stations.. 
