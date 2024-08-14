# Business-for-a-Hotel-Chain-Business
Business and Data Intelligence Implementation for a Hotel Chain Business
## 1. Introduction
AtliQ Grands, a prominent chain of five-star hotels across India, has been a key player in the hospitality industry for over 20 years. However, due to recent strategic moves by competitors and ineffective decision-making within management, the company has experienced a decline in both market share and revenue within the luxury and business hotel segments. In response, the managing director of AtliQ Grands decided to incorporate "Business and Data Intelligence" into their operations as a strategic initiative to regain their market share and enhance revenue streams.

Given the lack of an in-house data analytics team, AtliQ Grands engaged a third-party service provider to analyze historical data and provide actionable insights. This report outlines the process and results of the data analysis conducted.

## 2. Problem Statement
The primary challenge faced by AtliQ Grands was the loss of market share and revenue due to inadequate data-driven decision-making. The objective of this project was to leverage historical data to create a robust business intelligence system, providing the management team with key insights to guide strategic decisions and improve operational efficiency.

## 3. Project Tasks
The following tasks were undertaken to address the problem:

Metric Creation: Develop key metrics as per the provided metric list.
Dashboard Development: Create a comprehensive dashboard in Power BI based on the mock-up provided by stakeholders.
Insight Generation: Identify and present additional relevant insights that were not included in the original metric list or dashboard mock-up.

## 4. Data Processing and Transformation
The data analysis process began with loading the historical data into Power BI. The data was then transformed using Power Query, which included the following key steps:

Adding Week Number: Calculated the week number for each date.
Identifying Weekday vs. Weekend: Classified each day as a weekday or weekend.
Developing a Star Schema: A star schema relational database was designed to ensure accurate and efficient data extraction.

## 5. Key Measures Created
To support the analysis, the following key measures were developed in Power BI:

Revenue: Represents the total revenue realized from all bookings across the properties.

Total Bookings: Indicates the total number of bookings made across all properties.

Total Capacity: Reflects the total room capacity available across all hotels in the chain.

Total Successful Bookings: Captures the total number of successful bookings where guests checked out.

Occupancy Percentage: Measures the percentage of rooms occupied relative to the total capacity, providing insight into room utilization.

Average Rating: Shows the average customer rating, which is critical for assessing guest satisfaction.

Total Number of Days: Represents the total number of days covered in the data set, which is used for time-based analysis.

Total Cancelled Bookings: Reflects the number of bookings that were cancelled, which can inform strategies to reduce cancellations.

Cancellation Percentage: Indicates the percentage of total bookings that were cancelled, offering insight into booking reliability.

Total Checked Out: Represents the number of bookings that resulted in a successful checkout.

Total No-Show Bookings: Captures the number of bookings where guests did not show up without cancelling.

No-Show Rate: Measures the percentage of bookings where guests did not show up, helping to gauge booking commitment.

Booking Percentage by Platform: Illustrates the contribution of each booking platform to the total bookings, which is important for channel management.

Booking Percentage by Room Class: Shows the contribution of each room class (e.g., Standard, Deluxe) to the total bookings, which can guide pricing strategies.

Average Daily Rate (ADR): Represents the average revenue earned per occupied room per day, a key indicator of pricing effectiveness.

Realization Percentage: Reflects the percentage of bookings that were successfully realized (i.e., guests checked out), excluding cancellations and no-shows.

Revenue Per Available Room (RevPAR): Measures the revenue generated per available room, which is critical for assessing overall financial performance.

Daily Booked Room Nights (DBRN): Indicates the average number of rooms booked per day over the time period analyzed.

Daily Sellable Room Nights (DSRN): Reflects the average number of rooms available for sale per day.

Daily Utilized Room Nights (DURN): Captures the average number of rooms successfully utilized (i.e., guests checked out) per day.

Revenue Week-over-Week (WoW) Change Percentage: Measures the percentage change in revenue on a week-over-week basis, highlighting trends in revenue performance.

Occupancy WoW Change Percentage: Indicates the percentage change in occupancy on a week-over-week basis, showing trends in room utilization.

ADR WoW Change Percentage: Reflects the week-over-week percentage change in the Average Daily Rate, providing insight into pricing trends.

RevPAR WoW Change Percentage: Shows the percentage change in Revenue Per Available Room on a week-over-week basis, which helps in understanding revenue performance trends.

Realization WoW Change Percentage: Measures the percentage change in realization (successful checkouts) week-over-week, offering insights into guest commitment trends.

DSRN WoW Change Percentage: Indicates the week-over-week percentage change in Daily Sellable Room Nights, which is important for tracking changes in room availability.

## 6. Dashboard Development
A Power BI dashboard was created based on the stakeholder-provided mock-up. The dashboard includes key performance indicators (KPIs) such as revenue, occupancy, ADR, RevPAR, and customer satisfaction metrics, allowing the management to monitor performance and identify trends.

## 7. Insights Generated
In addition to the metrics specified, the analysis revealed several actionable insights:

## Revenue Trends by Room Type and Category:

1. The dashboard highlights that revenue generation is segmented between business and luxury room categories. The revenue for luxury rooms has shown a consistent higher performance compared to business rooms, though both categories have experienced fluctuations over the weeks.
The significant dip in revenue during week 32 for both categories suggests a potential external factor affecting bookings, warranting further investigation.
Occupancy Rates:

2. The overall occupancy rate across the properties is 57.87%. This metric indicates that there is potential to increase room occupancy, especially during off-peak times.
The occupancy percentage displayed on the dashboard suggests that there might be an opportunity to implement targeted marketing strategies to improve room bookings during low occupancy periods.
ADR and RevPAR Analysis:

3. The Average Daily Rate (ADR) of 12.7K suggests that pricing strategies are stable; however, the RevPAR Week-over-Week change percentage indicates a slight decline (-0.95%). This could be a sign of underutilization of available rooms, or a need to revisit pricing strategies during certain weeks.
Realization and Cancellation Rates:

4. The realization rate is quite healthy at 70.15%, indicating that the majority of bookings translate into successful check-outs.
However, the cancellation rate (24.83%) is relatively high, which could be mitigated through more flexible booking policies or targeted customer engagement efforts to reduce cancellations.
Booking Platform Insights:

5. The realization percentage and ADR are visualized across various booking platforms, with direct offline bookings showing a higher realization rate but lower ADR. This suggests an opportunity to optimize revenue by encouraging bookings through more profitable channels.
City-Wise Performance:

6. The revenue by city and property provides a granular view, with certain cities like Mumbai and Delhi showing stronger performance. This city-wise data can help focus marketing and operational efforts on underperforming locations to boost overall revenue.
Weekly Trends:

The trend analysis of key metrics like ADR, Occupancy %, and RevPAR over weeks provides a clear indication of how these metrics evolve, helping in identifying patterns and opportunities for tactical adjustments.

## 8. Recommendations
Based on the analysis and insights derived from the dashboard, the following recommendations are proposed:

1. Focus on High-Performing Cities: Enhance marketing efforts and customer engagement in cities like Mumbai and Delhi, where the properties are performing better, to capitalize on existing market strength.

2. Optimize Booking Channels: Encourage customers to use higher ADR platforms or direct booking channels, which have been identified as more profitable.

3. Address Cancellation Issues: Implement strategies to reduce the high cancellation rate, such as offering more flexible cancellation policies or incentives for customers who follow through with their bookings.

4. Enhance Occupancy During Low Periods: Use the weekly trend data to identify low-occupancy periods and implement targeted promotions or discounts during those times.

5. Investigate Revenue Dips: Further analyze the sharp decline in revenue during week 32 to understand the underlying causes and develop strategies to prevent similar occurrences in the future.

6. This comprehensive business and data intelligence approach will equip AtliQ Grands with the necessary tools to make informed decisions and regain their market share in the competitive luxury hotel industry.
