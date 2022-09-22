# Capstone-1-Hotel-Booking-Analysis

Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions!
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.
Explore and analyze the data to discover important factors that govern the bookings.


Column information
Hotel
H1: Resort hotel
H2: City hotel
is_canceled
1: Canceled
0: Not canceled
lead_time
No of days thaat elapsed between entering date of booking into property management system and arrival date
arrival_date_year
Year of arrival date (2015-2017)
arrival_date_month
Month of arrival date (Jan - Dec)
arrival_date_week_numberr
Week number of year for arrival date (1-53)
arrival_date_day_of_month
Day of arrival date
stays_in_weekend_nights
No of weekend nights (Sat/Sun) the guest stayed or booked to stay at the hotel
stays_in_week_nights
No of week nights (Mon - Fri) the guest stayed or booked to stay at the hotel
Adults
Children
Babies
meal
Type of meal booked. Undefined/SC – no meal package; BB – Bed & Breakfast; HB – Half board (breakfast and one other meal – usually dinner); FB – Full board (breakfast, lunch and dinner)
country
market_segment (a group of people who share one or more common characteristics, lumped together for marketing purposes)
TA: Travel agents
TO: Tour operators
distribution_channel (A distribution channel is a chain of businesses or intermediaries through which a good or service passes until it reaches the final buyer or the end consumer)
TA: Travel agents
TO: Tour operators
is_repeated_guest (value indicating if the booking name was from repeated guest)
1: Yes
0: No
previous_cancellations
Number of previous bookings that were cancelled by the customer prior to the current booking
previous_bookings_not_canceled
Number of previous bookings not cancelled by the customer prior to the current booking
reserved_room_type
Code of room type reserved. Code is presented instead of designation for anonymity reasons.
assigned_room_type
Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g. overbooking) or by customer request. Code is presented instead of designation for anonymity reasons.
booking_changes
Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation
deposit_type
Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories: No Deposit – no deposit was made; Non Refund – a deposit was made in the value of the total stay cost; Refundable – a deposit was made with a value under the total cost of stay.
agent
ID of the travel agency that made the booking
company
ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons
day_in_waiting_list
Number of days the booking was in the waiting list before it was confirmed to the customer
customer_type
Contract - when the booking has an allotment or other type of contract associated to it;
Group – when the booking is associated to a group;
Transient – when the booking is not part of a group or contract, and is not associated to other transient booking;
Transient-party – when the booking is transient, but is associated to at least other transient booking
adr (average daily rate)
required_car_parking_spaces
Number of car parking spaces required by the customer
total_of_special_requests
Number of special requests made by the customer (e.g. twin bed or high floor)
reservation_status
Canceled – booking was canceled by the customer;
Check-Out – customer has checked in but already departed;
No-Show – customer did not check-in and did inform the hotel of the reason why
reservation_status_date
Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel
