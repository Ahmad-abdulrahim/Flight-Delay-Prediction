Flight Delay Prediction

This NoSQL project utilizes MongoDB as the database to store and manage large volumes of flight data, including historical flight information and weather data. The project focuses on building flight delay prediction models using various machine learning techniques, such as regression, decision trees. The models will be trained on historical data and updated with realtime data to improve accuracy. The ultimate goal of the project is to provide airlines and passengers with more accurate and timely information about flight delays. 

Dataset source: https://www.kaggle.com/datasets/threnjen/2019-airline-delays-and-cancellations

A brief description of each column present in Flight Delay dataset:
• MONTH: The numerical month (1-12) of the flight.
• DAY_OF_WEEK: The numerical day of the week (1-7) of the flight.
• DEP_DEL15: A binary indicator (0/1) of whether the flight departed more than 15 minutes after the scheduled departure time.
• DEP_TIME_BLK: The time block of the scheduled departure time (e.g. "0600-0659" for departures scheduled between 6:00-6:59am).
• DISTANCE_GROUP: The distance group (in 250-mile intervals) of the flight.
• SEGMENT_NUMBER: The segment number of the flight.
• CONCURRENT_FLIGHTS: The number of other flights scheduled to depart within 2 hours of the given flight.
• NUMBER_OF_SEATS: The total number of seats available on the aircraft for the flight.
• CARRIER_NAME: The name of the airline carrier for the flight.
• AIRPORT_FLIGHTS_MONTH: The total number of flights departing from the airport in the given month.
• AIRLINE_FLIGHTS_MONTH: The total number of flights operated by the airline carrier in the given month.
• AIRLINE_AIRPORT_FLIGHTS_MONTH: The total number of flights operated by the airline carrier departing from the airport in the given month.
• AVG_MONTHLY_PASS_AIRPORT: The average monthly passenger traffic at the departing airport.
• AVG_MONTHLY_PASS_AIRLINE: The average monthly passenger traffic for the airline carrier.
• FLT_ATTENDANTS_PER_PASS: The number of flight attendants on the aircraft per available seat.
• GROUND_SERV_PER_PASS: The number of ground service personnel on the aircraft per available seat.
• PLANE_AGE: The age of the aircraft in years.
• DEPARTING_AIRPORT: The three-letter code of the departing airport.
• LATITUDE: The latitude coordinate of the departing airport.
• LONGITUDE: The longitude coordinate of the departing airport.
• PREVIOUS_AIRPORT: The three-letter code of the previous airport for the flight.
• PRCP: The total precipitation (in inches) for the day of the flight at the departing airport.
• SNOW: The total snowfall (in inches) for the day of the flight at the departing airport.
• SNWD: The total snow depth (in inches) for the day of the flight at the departing airport.
• TMAX: The maximum temperature (in degrees Fahrenheit) for the day of the flight at the departing airport.
• AWND: The average daily wind speed (in miles per hour) for the day of the flight at the departing airport.
