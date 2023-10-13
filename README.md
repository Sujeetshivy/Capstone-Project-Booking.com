Capstone Project

Booking.com
This capstone is divided into 4 Phase.

 Phase 1   
 Web scrapping the URL along 12 cities names provided at bottom of page.
Booking.com
https://www.booking.com/index.en-gb.html?aid=397646&label=yho748jc-1DCAEoggI46AdIM1gDaGyIAQGYAQm4ARfIAQzYAQPoAQGIAgGoAgO4Ap3Y96YGwAIB0gIkY2NlMDIyZmItZDdlZi00MWVkLWE5YzUtNmIzNmE1NWI3MDU32AIE4AIB&sid=0cb28093647b47834b4f3a02e11acd13&keep_landing=1&sb_price_type=total&

Go bottom of page and start navigating in CITIES tab:
12 Cities Name given below
1 Dubai, United Arab Emirates
2 London, United Kingdom
3 Kuala Lumpur, Malaysia
4 Manchester
5 New Delhi
6 Birmingham
7 Berlin
8 Sydney
9 Melbourne
10  Paris
11 Tokyo
12 Toronto

Phase 2
Make the table in csv format (3 csv files)
Data1.csv:   sno, Hotel name, cities, location, number of reviews, user ratings, star rating, review score
Data2.csv: sno, Hotel name, Free Wi-Fi, Family rooms, Non-Smoking Rooms, Restaurant, Bar, Heating, Lift, Breakfast Cuisine1, Breakfast Cuisine2, Breakfast Cuisine3
(Can take Yes /NO values)
Data3.csv:   sno, Hotel name, Room Type, Single Bed, Double bed,Prices

Write the SQL queries:
Table 1
1) Write a query to give details of hotels city is Sydney and ratings is more than 5.
2) Write a query to find the location with the most reviews.
3) Write a query that will retrieve all rows and sort them in descending order of user ratings.
4) Write a query that retrieves rows where the star rating is greater than or equal to 4.0 and sorts them in descending order of review score.
5) Write a query to count the number of hotels in each city. 

Table 2:
1)   Write a query to retrieve hotels that have both a restaurant and a bar
2) Write a query to retrieve hotels that offer free Wi-Fi and have family rooms.
3) Write a query to count the occurrences of each breakfast cuisine type.
4) Write a query to retrieve hotels that offer a certain(CONTINENTAL )  breakfast cuisine .{{Students you may give any cuisine as per your choices}}
5) Write a query to see whether an hotel has all amenities such as Heating, Lift and Bar.

Table 3:
1) Write SQL query to retrieve hotels that offer double bed rooms and sort them by price in descending order.
2) Write a SQL query to calculate the average price for each room type.
From here we will be making SUBQUERIES including the data from table 1/Table 2/Table 3
3) Write a query to find details of hotels with user ratings above 5 as a threshold and that offer free WiFi. (Use table 1 and table 2)
4) Write a query to find hotels that offer both family rooms and non-smoking rooms (Use table 1 and Table 2)

5) Write a query to calculate the average price for each room type (Use table2 and Table 3) 

Phase  3
 Now make only 1 data frame of 3 csv file using concat/merge /join operation of pandas and start doing EDA.
Do the complete EDA in details to explore the insights of data and write the detailed observations of each analysis. 

Phase 4
Write the complete Machine learning code to make predictions of price and review score. Use appropriate models on their label basis. Remember you need to make 2 different predictions: price and review score (Note: Inside Review score ---- Superb/Very good /Good /Pleasant)
Apply all the best techniques of scaling, hyperparameter tuning, avoid underfitting or overfitting (bias/variance)
At the end save the best model and convey on which basis you have chosen that model.

