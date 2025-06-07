# ITC-hotels-revenue-optimization
ITC Hotels Revenue Analysis Report :
Insights & Analysis
Page 1: Financial Overview & Revenue Performance
•	Revenue Distribution:
•	ITC Exotica generated the highest revenue in the Luxury category, while ITC Palace excelled in the Business category.
•	Elite room class contributed the most to overall revenue.
•	Cumulative Revenue:
•	Cumulative revenue trends were calculated using DAX to track revenue growth across the dataset's timeline.
•	Growth Analysis:
•	Month-over-Month (MoM) Growth: Calculated using previous month's revenue as the base.
•	Week-over-Week (WoW) Growth: Addressed challenges with incomplete week data by using week_of_year filtering instead of date-based calculations.
•	KPIs:
•	Average Daily Rate (ADR): ₹6.49K (calculated as room revenue divided by rooms sold).
•	Revenue Per Available Room (RevPAR): Derived by multiplying ADR with the occupancy rate.

________________________________________
Page 2: Occupancy & Capacity Analysis
•	Occupancy Rate:
•	Calculated as (checked_out + no_show) / total_capacity, yielding an overall rate of 43.5%.
•	Weekend occupancy was higher (47%) compared to weekdays (42%).
•	Seasonal Trends:
•	A strong positive correlation (0.45) between occupancy and revenue was identified.
•	RevPAR displayed a similar correlation with occupancy.
•	Insights:
•	Properties with higher occupancy rates generally had better revenue performance.

________________________________________
Page 3: Room Category Performance & Booking Insights
•	Revenue by Room Class:
•	Elite room class dominated revenue generation.
•	Bookings closer to the check-in date (2-3 days before) resulted in higher revenue.
•	KPIs:
•	Average Length of Stay (ALOS): Calculated per property and room class.
•	Average Booking Lead Time: Highlighted shorter booking windows for better revenue.
•	Trend Analysis:
•	Both MoM and WoW growth were calculated to track room class performance.

________________________________________
Page 4: Cancellations & Lost Revenue Analysis
•	Cancellation Rate:
•	Cancellation rate = (Number of cancellations / total bookings).
•	Patterns revealed peak cancellations in June and July, particularly in specific room types.
•	Lost Revenue:
•	Total revenue loss = SUM(revenue_generated) - SUM(revenue_realized).
•	Insights:
•	June witnessed the highest cancellations due to possible seasonality or customer preferences.
________________________________________
Conclusion & Recommendations :
•	ITC Hotels’ Elite room class and ITC Exotica’s Luxury category are the top-performing segments, warranting further investment and marketing efforts.
•	High weekend occupancy rates suggest targeted campaigns during weekdays could drive additional revenue.
•	Booking lead time and length of stay analyses indicate that shorter lead times correlate with higher revenue. Promoting last-minute deals could capitalize on this trend.
•	High cancellations during peak months highlight the need for a flexible cancellation policy or incentives to reduce cancellation rates.
