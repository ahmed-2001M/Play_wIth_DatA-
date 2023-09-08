# __About Dataset__
- __Link__ : https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction/code

- __Feature Description__ :
    - Gender: Gender of the passengers (Female, Male)

    - Customer Type: The customer type (Loyal customer, disloyal customer)

    - Age: The actual age of the passengers

    - Type of Travel: Purpose of the flight of the passengers (Personal Travel, Business Travel)

    - Class: Travel class in the plane of the passengers (Business, Eco, Eco Plus)

    - Flight distance: The flight distance of this journey

    - Inflight wifi service: Satisfaction level of the inflight wifi service (0:Not Applicable;1-5)

    - Departure/Arrival time convenient: Satisfaction level of Departure/Arrival time convenient

    - Ease of Online booking: Satisfaction level of online booking

    - Gate location: Satisfaction level of Gate location

    - Food and drink: Satisfaction level of Food and drink

    - Online boarding: Satisfaction level of online boarding

    - Seat comfort: Satisfaction level of Seat comfort

    - Inflight entertainment: Satisfaction level of inflight entertainment

    - On-board service: Satisfaction level of On-board service

    - Leg room service: Satisfaction level of Leg room service

    - Baggage handling: Satisfaction level of baggage handling

    - Check-in service: Satisfaction level of Check-in service

    - Inflight service: Satisfaction level of inflight service

    - Cleanliness: Satisfaction level of Cleanliness

    - Departure Delay in Minutes: Minutes delayed when departure

    - Arrival Delay in Minutes: Minutes delayed when Arrival

    - Satisfaction: Airline satisfaction level(Satisfaction, neutral or dissatisfaction)


# __From Univariate Analysis__
- __Usless Columns__
    - Unnamed: 0
    - id
- __Columns Have Nulls__
    - Arrival Delay in Minutes ==> 0.3%
- __Columns Have OutLiers__
    - Flight Distance
    - Departure Delay in Minutes
    - Arrival Delay in Minutes
- __Columns need Encoding__
    - __Ordinal__
        - Customer Type
        - satisfaction
    - __Nominal__
        - Gender
        - Type of Travel
        - Class


# __Feature Engineering__
- __Solve Problems__
    - Remove Unnamed: 0 and id Columns
    - Null values is so small so i will remove them
    - Replace Outliers with max value not outlier
- __Deal With Outliears__


- __Scale Data__
    - Use Standard Scaler to scale Age, Flight Distance and 