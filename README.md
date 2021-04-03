# NYC Citibike Analysis
---

## Overview
The purpose of this analysis is to take a sample of data from New York City's Citibike bike-sharing program to obtain valuable information to help decide if a similar program could be implemented elsewhere in Des Moines, Iowa. To begin this analysis, I obtained the program's ride data from August 2019 and used Python's pandas library to clean the data and correct the format of the dates and times and create an edited csv file. After this was completed, I used Tableau to efficiently visualize the data and gather important observations.

---

## Results

#### What are the typical durations of the bike trips?
The first question answered here takes data from every trip and shows us the count of trips that occured at each duration between 0 and 3 hours. The chart reveals that most trips are relatively short and the most common trip duration is only 5 minutes. After that it declines sharply as the duration increases.
![user_checkout_times](https://github.com/AndrewTymkiv/bikesharing/blob/main/images/user_checkout_times.PNG)

#### Do the trip durations differ by gender?
Next, I graphed the same data but filtered it by gender to see if the most common trip durations differed at all by gender, but they all followed the same relative shape and trend. The most common trip duration for males was 5 minutes, and for females it was 6 minutes.
![gender_checkout_times](https://github.com/AndrewTymkiv/bikesharing/blob/main/images/gender_checkout_times.PNG)

#### Trips by Weekday per Hour
This visualization shows what hours of the day the most trips occur for each day of the week, and reveals some expected results. From Monday through Friday, the number of trips increase between 7-9AM as people are leaving for work, and again between 5-7PM when people are leaving. However, the weekends experience increased trips during the afternoon time when most people are off work, peaking at around noon.
![trips_weekday_hour](https://github.com/AndrewTymkiv/bikesharing/blob/main/images/trips_weekday_hour.PNG)

#### Trips by Weekday by Gender
This visualization shows the same data again, but filtered by gender. All genders show the same trends.
![trips_gender_hour](https://github.com/AndrewTymkiv/bikesharing/blob/main/images/trips_gender_hour.PNG)

#### User Type Trips by Weekday by Gender
The Citibike program has two types of users: subscribers and customers. This visualization displays the weekdays where the most trips occur and is filtered by gender as well as the type of subscriber. It rveals the more trips come from subscribers and of those subscribers, more trips are taken by males. Number of trips seem to increase at the beginning and end of the week.
![user_trips_gender](https://github.com/AndrewTymkiv/bikesharing/blob/main/images/user_trips_gender.PNG)

#### Where are riders beginning and ending their trips?
These maps display the starting and ending locations of trips in the city. The larger and darker the circle, the more common the location is as a start or end point for the trips. The maps reveal that most of these trips begin and end in the downtown Manhattan area, likely due to the larger population there as well as the high number of tourists in this area.
![start_locations](https://github.com/AndrewTymkiv/bikesharing/blob/main/images/start_locations.PNG)
![end_locations](https://github.com/AndrewTymkiv/bikesharing/blob/main/images/end_locations.PNG)

#### 
https://public.tableau.com/profile/andrew.tymkiv#!/vizhome/Citibike_Challenge_16173892940010/NYCCitibikeStory?publish=yes
