# Hotel Data Analysis

![Icon](https://github.com/shridharkamathe/Hotel-Data-Analysis/assets/124047047/19abbba0-9335-44c8-821a-0d564ec3e032)


This repository contains an in-depth analysis of hotel bookings data, exploring various key performance indicators (KPIs) to provide insights into sales and bookings. The analysis also includes recommendations and strategies to improve sales and service within the hotel industry.

## Data Description

|Field|Description|
|---|---|

The dataset used for this analysis is sourced from multiple Excel files, including:
- 2015 Data.xlsx
- 2016 Data.xlsx
- 2017 Data.xlsx
- Combined Data.xlsx
- Data Description.xlsx

|Field|Description|
|---|---|
|hotel|Hotel (H1 = Resort Hotel or H2 = City Hotel)|
|is_canceled|Value indicating if the booking was canceled (1) or not (0)|
|lead_time|Number of days that elapsed between the entering date of the booking into the PMS and the arrival date|
|arrival_date_year|Year of arrival date|
|arrival_date_month|Month of arrival date|
|arrival_date_week_number|Week number of year for arrival date|
|arrival_date_day_of_month|Day of arrival date|
|stays_in_weekend_nights|Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel|
|stays_in_week_nights|Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel|
|adults|Number of adults|
|children|Number of children|
|babies|Number of babies|
|meal|Type of meal booked. Categories are presented in standard hospitality meal packages: Undefined/SC – no meal package; BB – Bed & Breakfast; HB – Half board (breakfast and one other meal – usually dinner); FB – Full board (breakfast, lunch and dinner)|
|country|Country of origin. Categories are represented in the ISO 3155–3:2013 format|
|market_segment|Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”|
|distribution_channel|Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”|
|is_repeated_guest|Value indicating if the booking name was from a repeated guest (1) or not (0)|
|previous_cancellations|Number of previous bookings that were cancelled by the customer prior to the current booking|
|previous_bookings_not_canceled|Number of previous bookings not cancelled by the customer prior to the current booking|
|reserved_room_type|Code of room type reserved. Code is presented instead of designation for anonymity reasons.|
|assigned_room_type|Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g. overbooking) or by customer request. Code is presented instead of designation for anonymity reasons.|
|booking_changes|Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation|
|deposit_type|Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories: No Deposit – no deposit was made; Non Refund – a deposit was made in the value of the total stay cost; Refundable – a deposit was made with a value under the total cost of stay.|
|agent|ID of the travel agency that made the booking|
|company|ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons|
|days_in_waiting_list|Number of days the booking was in the waiting list before it was confirmed to the customer|
|customer_type|Type of booking, assuming one of four categories: Contract - when the booking has an allotment or other type of contract associated to it; Group – when the booking is associated to a group; Transient – when the booking is not part of a group or contract, and is not associated to other transient booking; Transient-party – when the booking is transient, but is associated to at least other transient booking|
|adr|Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights|
|required_car_parking_spaces|Number of car parking spaces required by the customer|
|total_of_special_requests|Number of special requests made by the customer (e.g. twin bed or high floor)|
|reservation_status|Reservation last status, assuming one of three categories: Canceled – booking was canceled by the customer; Check-Out – customer has checked in but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why|

## Analysis

The analysis covers the following aspects:

1. **Data Cleaning and Consolidation:** The data from different Excel files is cleaned and combined into a single dataset, ready for analysis.

2. **Exploratory Data Analysis (EDA):** Various KPIs are calculated and visualized to gain insights into sales trends, booking patterns, customer preferences, and room occupancy rates.

3. **Dashboard Creation:** A dynamic and interactive dashboard is created to visually represent the analyzed data. The dashboard provides a comprehensive view of the hotel's performance and allows users to explore different metrics and time periods.

4. **Sales and Booking Insights:** The analysis delves into key insights such as peak booking periods, popular room types, average length of stay, and revenue trends.

5. **Recommendations and Strategies:** Based on the insights obtained, actionable recommendations and strategies are proposed to improve sales and enhance the overall customer experience. These may include targeted marketing campaigns, pricing adjustments, and service enhancements.

|Insights|
|---|
|34% of the total bookings were cancelled in 2015,2016,2017|
|City Hotels had higher cancellation rate (23.9%) than that of Resort Hotels(10.7%).|
|Only 3% are repeated guests. Customer Retention is low|
|71.8% of customers are transient type, 22.5% are transient Party, 5.5% are contract type and only 0.2% belong to Contract type.|
|86% of guests didn't make any booking changes. 9.7% made only 1 booking changes.|
|Agent ID number 9 made the highest bookings which is 705.|
|94% Guests did not require car parking space, hence a portion of car parking space can be used for some activity to increase guest involvement.|
|82.3% bookings were done through TA/TO channel, 11.6% were direct , 5.8% were Corporate and 0.1% were GDS.|
|Room type 'A' is most preferred by gueses, followed by room 'D', 'E' , 'F' , 'G' , 'C' , 'B' , 'H'.|
|90% of guestes prefer 'No Deposit' type of criteria, followed by 9.6% 'Refundable' and rest 'Refundable'.|
|BB (breakfast Bed) is the most preferred meal type followed by , HB(Half Board),SC(Self Catering),FB(Full Board).|
|For Resort Hotel, June to September is the peak bookings period and for City Hotel bookings increase from January to September and drop sharply from October to November.|
|Resort Hotel had higher ADR than City Hotel in July and August but in other months, ADR of City Hotels is higher than that of Resort Hotels.|
|Portugal had the highest number of guests followed by Great Britain, Spain, Germany , Italy, Ireland, Brasil, USA, Belgium.|
|City Hotels has higher waiting time on average than that of Resort Hotel.|
|TA/TO has highest adr for City hotels as well as Resort Hotels.|
|TA/TO has highest cancellations, in order to reduce the cancellations they should improve their cancellation policies.|
|Out of the booking cancellation, 98% did not cancel their booking because of not getting assigned the same room as reserved|
|Lead Time and Total Stay is positively correlated hence more the stay of customer, more will be the lead time.|
|Average number of stays in both City as well as Resort hotel is 3.63 Days.|
|Average ADR is 101.|


## Repository Structure

The repository is structured as follows:

- **data:** This directory contains the raw and cleaned datasets in Excel format.

- **dashboard:** This directory contains files related to the interactive dashboard created for data visualization.

- **README.md:** This file, providing an overview of the repository and its contents.

## Usage

To explore the hotel data analysis and access the interactive dashboard:

1. Clone or download this repository to your local machine.
2. Dashboard is available in Hotel Data Analysis.xlsx file.
3. Customize and modify the analysis and dashboard as required for your specific use case.

## Contributing

Contributions to this repository are not currently being accepted, as it is a sample repository. However, feel free to fork the repository and adapt it to your own requirements.

## Acknowledgments

We would like to acknowledge the efforts put into this analysis and the creation of the interactive dashboard. The insights and strategies provided are based on thorough research and data exploration.

Please note that this analysis and the resulting recommendations should be further evaluated and adapted based on the specific context and objectives of the hotel business.
