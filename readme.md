# (Ford GoBike System Data Exploration))
## by (Mohamed Refaiy)


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.<br>
>There are 183,412 trip data in this data set with 16 features (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, and bike_share_for_all_trip).<br>
>Most variables are numeric in nature. Columns (start_station_id, start_station_name, end_station_id, end_station_name, member_birth_year, and member_gender) have some null values.


## Summary of Findings

>1. **Trip duration mean is not afected by age group, even for younger age group they tend to do more trips, and the duration is more right skewed.**
>1. **trips with same same start and end station are about 2% of all trips, with 14 percent could be done by mistake trips as it's duration were less than 2 minutes.**
>1. **Same start and end stations trips have diffrent rush hours from 11 AM to 5 PM.**
>1. **Rush hours per week days are same with 2 peaks, while on weekends there only 1 rush hour around 2 PM.**
>1. **In weekends there noticable activity in late hours.**
>1. **After 6 PM till 5 AM people in twenties are the main users, while in rest of day people in thirties are the main users.**
>1. **The majority of users are subscriber.**

## Key Insights for Presentation

> **People debend on GoBike system as an alternative of walking or waiting while there is a traffic jam, with average trip duration around 11 minutes and over than 75% of trips duration are below 15 mintues. In addition to that only a very small percent of trips were completey done through bike. People in twenties and thirties repesent the main age of users. Excluding weekends There is 2 peaks every day from 7 AM to 9 AM, and from 4 PM to 6 PM, when every one trying to be at work on time or want to go home ASAP. In weekdends afternoon hours are the peak hour with a noticeable increase in very late hours. After 6 PM till 5 AM people in twenties are the main users, while in rest of day people in thirties are the main users.The majority of users are subscriber which can be a sign of high convertion rate.**
