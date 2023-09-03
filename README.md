# Hotel-Booking-Analysis

Hotel industry is a complicated field for data analysis. Hotel performance depends on a lot of variables: location, room types distribution, meals, tour operators, time of the year flights capacity, etc.
Booking data is the one of the most granular data in the hotel industry from the perspective of the revenue: one can disclose time paterns or try to predict outcomes like wheter a booking will end up in a cancellation.
The data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.
Explore and analyze the data to discover important factors that govern the bookings.


# Dataset information
This dataset contains booking information for a city hotel and a resort hotel. It contains the following features.

1. hotel: Name of hotel ( City or Resort)
2. is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
3. lead_time: time (in days) between booking transaction and actual arrival.
4. arrival_date_year: Year of arrival
5. arrival_date_month: month of arrival
6. arrival_date_week_number: week number of arrival date.
7. arrival_date_day_of_month: Day of month of arrival date
8. stays_in_weekend_nights: No. of weekend nights spent in a hotel
9. stays_in_week_nights: No. of weeknights spent in a hotel
10. adults: No. of adults in single booking record.
11. children: No. of children in single booking record.
12. babies: No. of babies in single booking record.
13. meal: Type of meal chosen
14. country: Country of origin of customers (as mentioned by them)
15. market_segment: What segment via booking was made and for what purpose.
16. distribution_channel: Via which medium booking was made.
17. is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for Yes)
18. previous_cancellations: No. of previous canceled bookings.
19. previous_bookings_not_canceled: No. of previous non-canceled bookings.
20. reserved_room_type: Room type reserved by a customer.
21. assigned_room_type: Room type assigned to the customer.
22. booking_changes: No. of booking changes done by customers
23. deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
24. agent: Id of agent for booking
25. company: Id of the company making a booking
26. days_in_waiting_list: No. of days on waiting list.
27. customer_type: Type of customer(Transient, Group, etc.)
28. adr: Average Daily rate.
29. required_car_parking_spaces: No. of car parking asked in booking
30. total_of_special_requests: total no. of special request.
31. reservation_status: Whether a customer has checked out or canceled,or not showed
32. reservation_status_date: Date of making reservation status.

Total number of rows in data: 119390

Total number of columns: 32

# Conclusion:

1. Majority of the hotels booked are city hotel. Definitely need to spend the most targeting fund on those hotel.
2. City hotels have the highest cancellation rates, this can be verified by the fact that city hotels have higher booking rate than resort hotels.
3. 2016 has more number of bookings than 2015 and 2017. After 2015 bookings increased in 2016 but then decreased in 2017.
4. From above we can see that month ending has the least number of arrivals in both resort and city hotels.
5. August month has the highest number of bookings.Month of November, December and January has the lowest number of Bookings.
6. For both city and resort hotels, Nov to Jan have cheaper average daily rates.
7. Frow above we see that the majority of the distribution channels and market segments involve travel agencies (online or offline). We can target our marketing area to be on these travel agencies website and work with them since majority of the visitors tend to reach out to them.
8. The highest number of visitors are from Europe namely Portugal(PRT),United kingdom(GBR),France(FRA) and Spain(ESP).

# Hotel Booking Analysis Dashboard

https://public.tableau.com/views/HotelBookingAnalysis_16901491256210/HotelBooking1?:language=en-US&:display_count=n&:origin=viz_share_link

![tableau dashboard](https://github.com/Gaurav-Yaduvanshi/Hotel-Booking-Analysis/assets/99022806/6801d468-63c4-4a7f-95f7-a9c9ecab210e)
