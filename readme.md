# 2019 Fordgobike Dataset Exploration and Visualization
## by Mahmoud Osama


## Dataset
> We will investigate  **Ford GoBike System Dataset**, assess its quality and tidiness, then clean it which called data wrangling. 

>**Ford GoBike System Dataset**  includes information about individual rides made
in a bike-sharing system covering the greater San Francisco Bay area.

> our dataset orginally consists of 183,412 row (records) and 16 columns and Most variables are numeric and concerns three major things as follow: 
>        
    - Trip (duration_sec, start_time, end_time)
    - station (start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude)
    - User (bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip)
 
> After adjustment and cleaning process new columns were created to help in analyzing and expolring the data so, our dataset consists of 21 columns now and the new columns as follow:
>
    - Trip (duration_min, start_date, Trip_day of the week, Trip_hour of the day)
    - User (member_age)

## Summary of Findings

>   
    - Most users are Subscribers and Dominant gender is Male 
    - User with Age between 25 and 35 are making top of number of trips 
    - Most of trips are taking less than 15 mins and most trips takes about 10 mins.
    - The lowest number of trips are in the weekend holiday (Saturday and Sunday) while the top number of the trips is on Thursday the last working day of the week.
    - the rush hours of number of trips are 8 (8 am)and 17 (5 pm) while the number of the trips is the least and decreasing rapidly after midnight until dawn
    - Subscribers tends to rent bikes on working days while Customers tends to rent more in the weekend holiday (Saturday and Sunday) for longer duration.
    - Subscribers tends to rent bikes for shorter duration while Customers tends to rent bikes for longer duration
    - Both of Users type have their trips duration decreases as age increases and Subscribers of old age (60-80) have a longer trip duration and larger no of trips from customers.


## Key Insights for Presentation

> User Type and their Weekdays Usage:
>
    - Most users are Subscribers
    - Subscribers have the lowest number of trips in the weekend holiday (Saturday and Sunday) while Customers have the lowest number of trips on Wednesday and have realtively better numbers of trips in the weekend holiday (Saturday and Sunday).
    
    
> User Type and their Trips Duration:
>   
     - Most of trips are taking less than 15 mins and the top number of the trips takes about 10 mins.
     - Subscribers have narrower trip duration than Customers
     - Subscibers have more specific Trips than casual Customers
     
> Trips Duration in Week days per User type:
>    
    - Subscribers tends to rent bikes on working days while Customers tends to rent more in the weekend holiday (Saturday and Sunday) for longer duration.
    - Subscribers rent bikes more efficiently as they have a shorter trip duration overall than customers.
    - Both of Users type have a longer trip duration on weekend in relative to their trips during other week days.


