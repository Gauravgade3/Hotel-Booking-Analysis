# Hotel-Booking-Analysis
## Analysing the data of Hotel Booking

This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.

We will perform exploratory data analysis with python to get insight from the data.

This article on medium explains the entire the process
Exploratory Data Analysis of the Hotel Booking Demand with Python

## Table of Content

Motivation

Tools and Libraries Used

Files

Result
## Motivation

## We have tried to answer the following Questions

1. How Many Booking Were Cancelled?

2. What is the booking ratio between Resort Hotel and City Hotel?

3. What is the percentage of booking for each year?

4. Which is the most busy month for hotel?

5. From which country most guest come?

6. How Long People Stay in the hotel?

Which was the most booked accommodation type (Single, Couple, Family)?
## After that we made the predictive model to predict whether the booking will be cancelled or not
We will:

Perform the Feature Engineering to make new featuers

Perform the Data Selection to select only relevant features

Visualize the data with the help of charts and graphs

Finally came with few insights by analyzing them .

## Tools and Libraries Used
We have used Python 3 to its following packages:

Pandas
Matplotlib
Seaborn
Sklearn
## Files
This repository contains two files other than readme file

Hotel Booking.ipynb: Jupyter Notebook file contains all the python code, documentation and visualization
hotel_bookings.csv: Our dataset file

Dataset contains following features:

hotel

is_canceled

lead_time

arrival_date_year

arrival_date_month

arrival_date_week_number

arrival_date_day_of_month

stays_in_weekend_nights

stays_in_week_nights

adults

children

babies

meal

country

market_segment

distribution_channel

is_repeated_guest

previous_cancellations

previous_bookings_not_canceled

reserved_room_type

assigned_room_type

booking_changes

deposit_type

agent

company

days_in_waiting_list

customer_type

adr

required_car_parking_spaces

total_of_special_requests

reservation_status

reservation_status_date

## Result
We learned that

Almost 35% of bookings were canceled.

More than 60% of the population booked the City hotel.

More than double bookings were made in 2016, compared to the previous year. But the bookings decreased by almost 15% next year.

Most bookings were made from July to August. And the least bookings were made at the start and end of the year.

Portugal, the UK, and France, Spain and Germany are the top countries from most guests come, more than 80% come from these 5 countries.

Most people stay for one, two, or three. -> For Resort hotel, the most popular stay duration is three, two, one, and four days respectively. -> For City hotel, most 
popular stay duration is one, two, seven(week), and three respectively
Couple (or 2 adults) is the most popular accommodation type. So hotels can make arrangement plans accordingly
