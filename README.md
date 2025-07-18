# Cyclistic Case Study

## Overview
This project is the final capstone of the Google Data Analytics Professional Certificate on Coursera. It focuses on a case study involving Cyclistic, a fictional bike-share company based in Chicago. The ultimate goal is to analyze historical trip data to uncover insights that will help the marketing team convert casual riders into annual members.

## Business Task
Use historical trip data to identify trends in how casual riders and annual members differ and provide recommendations to convert casual riders into annual members.

## Data Source
The data used in this project has been made available by Motivate International Inc. under this [license](https://divvybikes.com/data-license-agreement). It includes [12 months of Cyclistic trip data](https://divvy-tripdata.s3.amazonaws.com/index.html) from January to December 2024. 

## My Process
1. Used Power Query in Excel to load and combine 12 months and over 5 million rows of trip data from CSV files.
2. Removed unnecessary columns (e.g., latitude/longitude, etc.).
3. Added columns for hour, month, and name of day.
4. Created a custom column to determine ride duration by subtracting 'started_at' from 'ended_at' times and converting format to minutes.
5. Created a conditional column to categorize ride durations into 15-minute intervals up to 60 minutes for easier analysis before removing the original column.
6. Removed 'started_at' and 'ended_at' columns once no longer needed.
7. Used 'Group By' to aggregate data by rows and count the number of occurrences for each unique combination of values.
8. Used pivot tables and charts to visualize data and make observations.
9. Created a PowerPoint presentation and a Tableau dashboard to exhibit findings.

## Key Findings
1. Rides by Hour: Casual use concentrates midday, while member rides peak at 8 AM and 5 PM.
2. Rides by Day of Week: Casual riders peak on weekends, while members ride more during the week.
3. Rides by Month: Overall usage peaks during warm months and declines during cold months.
4. Ride Duration: More casual riders take longer rides than members, despite being fewer in number.

## Recommendations
1. Offer monthly or seasonal memberships to support high demand in the summer while bridging the gap between casual and annual membership.
2. Offer exclusive member benefits during weekends and afternoons/evenings when casual riders are most active. 
3. Run targeted campaigns highlighting the cost savings of annual membership for casual riders who take longer, pricier rides. 

## Links 
[View My Tableau Dashboard](https://public.tableau.com/views/CyclisticDashboard_17524460647350/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Conclusion
This project demonstrates the practical application of data analytics tools and processes to solve real-world business problems. The insights it provides can help Cyclistic make informed marketing decisions to grow its base of annual members and drive organizational success.
