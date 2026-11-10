# Arlene_20252SEN280_LuxeStayHotel

## Project title: LuxeStay Hotel

Project subtitle: Smart Hotel Reservation and Management System

## Project description:

LuxeStay Hotel is an Oracle database application designed to manage hotel operations, including guest registration, room reservations, room allocation, check-in and check-out, billing and payment processing. The system will use PL/SQL to automate reservation cancellations, calculate applicable refunds, prevent double bookings and monitor hotel revenue.

## A. Problem statement

Many hotels face challenges managing guest information, room reservations, cancellations, payments and room availability, especially when these activities are handled manually or through disconnected systems. These challenges can lead to double bookings, inaccurate billing, poor tracking of cancellations and difficulties monitoring hotel revenue. And the problem of reserving a room and then don't show up.

LuxeStay Hotel proposes an integrated database system that automates these operations using Oracle PL/SQL, improving the accuracy, efficiency and reliability of hotel management.

## B. Project objectives

To develop an Oracle database management system using PL/SQL to improve hotel reservation, room allocation, cancellation of reservation and billing operations and refunds if any.

Specific objectives
1. To develop a database for managing guest registration, room information and reservations.
2. To automate booking, cancellation reservation, check-in and check-out processes using PL/SQL.
3. To implement automatic bill and refund calculations.
4. To prevent overlapping room reservations and maintain accurate room availability.
5. To develop an interactive dashboard for monitoring hotel reservations and financial performance.

## C. Proposed solution

The system will provide a centralized database where hotel receptionists can register guests, manage room reservations, record check-ins and check-outs, and process payments.

It will also include smart cancellation of reservation and refund management, automatic room availability checking and a revenue dashboard connected to the Oracle database.

## Database tables

These are the tables going to be used to create our system:


1.	GUESTS :	Store guest information
2.	ROOMS :	Stores room details
3.	ROOM_TYPES :	Stores room categories and prices
4.	RESERVATIONS :	Store booking records
5.	CANCELLATIONS :	Store cancellation information
6.	CHECK_INS :	Store guest arrival records
7.	CHECK_OUTS :	Store departure records
8.	SERVICES :	Store additional hotel services
9.	SERVICE_USAGE :	Track services used by guests
10.	BILLS :	Store guest bills
11.	PAYMENTS :	Store payment records
12.	REFUNDS :	Store refund transactions
13.	AUDIT_LOG :	Track important database changes
14. LOYALTY_ACCOUNTS :	Stores each guest's loyalty account and points balance
15. LOYALTY_TRANSACTIONS	: Records points earned and redeemed
16. MEMBERSHIP_TIERS	: Stores Bronze, Silver, Gold, and Platinum levels
17. REWARDS	: Stores available guest rewards
18. REWARD_REDEMPTIONS	: Records rewards redeemed by guests


## Data source link
 This include all the dataset information going to be used in our project
 this is the link:

 https://www.kaggle.com/code/jillanisofttech/data-anaylsis-hotel-booking-project/input

Another link:

https://doi.org/10.1016/j.dib.2018.11.126?utm_source=chatgpt.com

 ## My innovation

LuxeStay Hotel  main innovation is a VIP Guest Recognition and Loyalty Rewards System that identifies returning guests and rewards them for their loyalty. The system will automatically calculate loyalty points based on eligible completed stays and spending, assign membership levels, and allow qualified guests to redeem rewards. Using Oracle PL/SQL, the system will automate these processes, maintain accurate guest loyalty records, and help hotel management improve guest satisfaction and encourage repeat bookings.

## Planned PL/SQL features

1. Stored Procedures
Procedures will perform important hotel operations automatically.
- Register new guests.
- Create and manage room reservations.
- Allocate available rooms to guests.
- Process guest check-in and check-out.
- Generate guest bills.
- Record guest payments.
- Process reservation cancellations.
- Register loyalty accounts for guests.
- Redeem loyalty rewards.
  
2. Functions
Functions will calculate and return important information.
- Calculate the total cost of a reservation.
- Calculate additional service charges.
- Calculate the remaining balance after payments.
- Check room availability.
- Calculate loyalty points earned by guests.
- Determine guest membership levels (Bronze, Silver, Gold, and Platinum).
- Calculate a guest's total spending and completed stays.
  
3. Triggers
Triggers will automatically enforce hotel business rules when database events occur.
- Prevent double booking of hotel rooms.
- Update room status after check-in and check-out.
- Automatically update reservation status.
- Record important database activities.
- Award loyalty points after an eligible completed stay.
- Update a guest's VIP membership level when they meet the required conditions.
- Prevent invalid loyalty point redemption.
  
4. Cursors
Cursors will help retrieve and process multiple records.
- Display all available hotel rooms.
- Generate lists of guests with active reservations.


## Refences :

## 1. Research papers:

 Reference 1: Hotel loyalty programs and customer loyalty

Koo, B., Yu, J., & Han, H. (2020). The role of loyalty programs in boosting hotel guest loyalty: Impact of switching barriers. International Journal of Hospitality Management, 84, Article 102328. https://doi.org/10.1016/j.ijhm.2019.102328


Reference 2: Membership levels and guest loyalty

Lee, J. J., Tsang, N., & Pan, S. (2015). Examining the differential effects of social and economic rewards in a hotel loyalty program. International Journal of Hospitality Management, 49, 17–27. https://doi.org/10.1016/j.ijhm.2015.05.003


## 2. Industry report and statistics

Reference 3: Rwanda Development Board Annual Report 2024

Rwanda Development Board. (2025). Annual report 2024. https://rdb.rw/ar/Annual-report-2024.pdf


## 3. Existing hotel system

Reference 4: Marriott Bonvoy

Official website: https://www.marriott.com/loyalty/member-benefits.mi?utm_source=chatgpt.com

link: https://www.marriott.com/loyalty/redeem.mi?utm_source=chatgpt.com  
For understanding how rewards can be used. 


## 4. Dataset

Reference 5: Hotel Booking Demand Dataset

Antonio, N., de Almeida, A., & Nunes, L. (2019). Hotel booking demand datasets. Data in Brief, 22, 41–49. https://doi.org/10.1016/j.dib.2018.11.126
