# EDA-of-bookings-and-ML-to-predict-cancelations

## Hotel booking
Content:
1. EDA
The dataset contains data from two different hotels. One Resort hotel and one City hotel.

From the publication (https://www.sciencedirect.com/science/article/pii/S2352340918315191) we know that both hotels are located in Portugal (southern Europe) ("H1 at the resort region of Algarve and H2 at the city of Lisbon"). The distance between these two locations is ca. 280 km by car and both locations border on the north atlantic.

The data contains "**bookings due to arrive between the 1st of July of 2015 and the 31st of August 2017**".
Note: _For most questions I will only use bookings that were not canceled, to get acutal guest numbers. As you will see, this is quite a big difference._

>[Questions]
>Topics covered and questions to answer from the data:

+ Where do the guests come from?
+ How much do guests pay for a room per night?
+ How does the price per night vary over the year?
+ Which are the most busy month?
+ How long do people stay at the hotels?
+ Bookings by market segment
+ How many bookings were canceled?
+ Which month have the highest number of cancelations?
+ Do you have more questions? Tell me in the comments and I will see if I can answer them. :)

2. Predicting cancelations
It would be nice for the hotels to have a model to predict if a guest will actually come.
This can help a hotel to plan things like personel and food requirements.
Maybe some hotels also use such a model to offer more rooms than they have to make more money... who knows...

3. Evaluate Feature importance
Which features are most important to predict cancelations?

## Datasets Description
+ hotel 🏩_Hotel H1 = Resort Hotel or H2 = City Hotel)_
+ is_canceled ❌_Value indicating if the booking was canceled (1) or not (0)_
+ lead_time ⌚_Number of days that elapsed between the entering date of the booking into the PMS and the arrival date_
+ arrival_date_year 📆_Year of arrival date_
+arrival_date_month 📅_Month of arrival date_
+ arrival_date_week_number 🗓_Week number of year for arrival date_
+ arrival_date_day_of_month 📆_Day of arrival date_
+ stays_in_weekend_nights 🌃_Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel_
+ stays_in_week_nights 💤_Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel_
+ adults 👨🏻👩🏻_Number of adult_
