
# Hotel Booking Analysis

## Table of Content

1. Introduction
2. Problem Statement
3. Dataset Information
4. Conclusion

<p align="center">
  <img 
    width="750"
    height="400"
    src = "https://chl.co.in/front_assets/images/content1.gif">
</p>


*****
1. Introduction

This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.
  
2. Problem Statement

Our main objective is to perform EDA on the given dataset and draw useful conclusions about general trends in hotel bookings and how factors governing hotel bookings interact with each other.

3.  Dataset information

We are given a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. It contains the following features.

    - hotel: Name of hotel ( City or Resort)
    - is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
    - lead_time: time (in days) between booking transaction and actual arrival.
    - arrival_date_year: Year of arrival
    - arrival_date_month: month of arrival
    - arrival_date_week_number: week number of arrival date.
    - arrival_date_day_of_month: Day of month of arrival date
    - stays_in_weekend_nights: No. of weekend nights spent in a hotel
    - stays_in_week_nights: No. of weeknights spent in a hotel
    - adults: No. of adults in single booking record.
    - children: No. of children in single booking record.
    - babies: No. of babies in single booking record. 
    - meal: Type of meal chosen 
    - country: Country of origin of customers (as mentioned by them)
    - market_segment: What segment via booking was made and for what purpose.
    - distribution_channel: Via which medium booking was made.
    - is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for 
                         Yes)
    - previous_cancellations: No. of previous canceled bookings.
    - previous_bookings_not_canceled: No. of previous non-canceled bookings.
    - reserved_room_type: Room type reserved by a customer.
    - assigned_room_type: Room type assigned to the customer.
    - booking_changes: No. of booking changes done by customers
    - deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
    - agent: Id of agent for booking
    - company: Id of the company making a booking
    - days_in_waiting_list: No. of days on waiting list.
    - customer_type: Type of customer(Transient, Group, etc.)
    - adr: Average Daily rate.
    - required_car_parking_spaces: No. of car parking asked in booking
    - total_of_special_requests: total no. of special request.
    - reservation_status: Whether a customer has checked out or canceled,or not showed 
    - reservation_status_date: Date of making reservation status.
  dataset have 119390 records and 32 features.

4. Conclusions:

      * In the both hotel, most of the customers are no deposite type.
      * Frequent guest visit both hotel in same proportion, maximum number of new guest visit city hotel.
      * Most of the visitor who book their room are from aviation industry
      * travel agent or tour operator are most popular distribution channel.
      * Maximum number of visitor from Portugal followed by Great Britain and France.
      * For Portugal and great Britain resort hotel is more popular, from France onwards city hotel is more popular.
      * Very small amount Aviation people cancel their ticket compare to online TA
      * BB is the most popular food for both the hotel.
      * People with night stay 4 or more preferred to book room in resort hotel and less than 4 preferred to book in city hotel.
      * booking change is increases from January to July and reaches to its maximum value and then decreases to December. 
      * every four-month waiting time increases to its maximum value

