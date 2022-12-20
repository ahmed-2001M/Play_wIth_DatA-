__Notes__

- data have 1156 row and 7 columns
- start and end dates need to convert to datetime

    __Feature Engeneering__

    - we can get from date time
        1) day name
        2) day parts
        3) hour
        4) trip time
        
    - we can get driving speed from miles and trip time
- there was unknow values
- replace trip time with 0 to null
- binning for miles
- binning for trip time

    __Observations__

    - there are 128 diffrent start point
    - cary and morrisiville are the most start and end points 
    - most trips take range from  0 to 10 miles
    - popular purposes for trips are Meetings , Meals, Entertain and Errand  
    - fridaay , tusday and monday are the most days have trips
    - afternoon the highest time of the day has trips
    - Ride durations range from 2 minutes to 330 minutes
    - evening the most time have short time trips