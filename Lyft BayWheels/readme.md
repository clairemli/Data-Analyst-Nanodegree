# Lyft Bay Wheels Data Exploration
## by Claire Li


## Dataset

This project uses trip data from Lyft's Bay Wheels, a bikeshare service based in San Francisco, CA. The goal of this project is to glean insights about the service from the dataset using data visualizations. Features included in the dataset (taken from Lyft's website) were: ride ID, type of bike, start and end time/date, start and end station ID, start and end station name, start and end station coordinates, and user type.   


## Summary of Findings

Some key findings include: 
* **Peak hours**: More rides were taken on weekends, with the peak of activity being on Memorial Day weekend. Peak hours during the day were around 12PM - 5PM. During the week, number of rides generally increases from 12PM to 5PM, and then tapers down. During the weekend, the peak occurs around 2-3PM. During off-hours, which can be loosely described as 12AM - 4AM and after 8PM, number of rides was about the same across all days of the week. 
* **Ride details**: Removing outliers, it was found that the average trip lasts around 15-30 minutes and the average distance betwen start and end station is somewhere between 0.5 - 1.0 miles. 3 geographical clusters (corresponding to major cities) were identified: San Francisco, San Jose, and Oakland/Berkeley. Rides starting from Oakland/Berkeley tended to have higher average duration, while rides starting from San Francisco had the highest average distance. 
* **Member information**: Most riders are non-members. Members are mostly from San Francisco, with approximately equal numbers of members and non-members in San Jose and Oakland/Berkeley. 

## Key Insights for Presentation

From a business perspective, I found the most valuable insights to be: 
1. **Peak hours**: Peak hours can generally be described as being between 12PM-5PM. On weekdays, number of rides increases from 12PM - 5PM and then tapers down; on weekends, number of rides is highest at approximately 2-3PM. Weekends see higher volume of rides. 
2. **Ride details**: Rides are generally between 15-30 minutes, and 0.5-1.0 miles. Significantly more rides are taken in San Francisco than other areas, offering an opportunity for expansion. 
3. **Member information**: Most riders are casual users (i.e., non-members). Members are mostly located in San Francisco, again indicating an opportunity for expansion. 
