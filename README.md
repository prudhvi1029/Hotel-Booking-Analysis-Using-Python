# Hospitality Data Analysis Project using Python 🏨📊

AtliQ Grands struggled to achieve revenue goals amidst tough competition in the luxury hotel industry. As a growing Data Analyst, I took on the challenge of reshaping the success story of this 5-star hotel chain in India.

## About AtliQ Grands

- **Five-Star Luxury:** AtliQ Grands is a chain of five-star hotels with locations in four busy cities.  
- **Strategic Presence:** With seven unique properties across these cities, AtliQ Grands serves a variety of guests.  
- **Personalized Guest Experience:** Guests can choose from four types of rooms—Elite, Premium, Presidential, and Standard—to suit their preferences.  
- **Easy Booking Options:** Guests can book their stay through six popular online platforms, ensuring convenience and flexibility.  

This project uses data analysis to uncover valuable insights and create strategies that increase revenue, improve operations, and boost guest satisfaction.
## Table of Contents  
**1. Overview**

**2. Datasets**

**3. Column Descriptions**

**4. Key Insights from the Hotel Booking Analysis Project 🏨📊**

**5. Recommendations Based on Insights 🌟📋**


---

## Overview  

This project utilizes **Python** and **Jupyter Notebook** to analyze hotel booking data from five key datasets. The analysis provides insights into revenue trends, occupancy rates, customer ratings, booking platforms, and seasonal patterns.  

The objectives include:  
- Identifying high-performing room categories and locations.  
- Uncovering seasonal demand trends.  
- Optimizing booking platforms and pricing strategies.  
- Improving customer satisfaction in low-rating locations.  

---

## Datasets  

The project uses the following datasets, provided as CSV files:  

1. **`dim_date`** – Date-related metadata.  
2. **`dim_hotels`** – Information on hotel properties.  
3. **`dim_rooms`** – Room categories and classes.  
4. **`fact_aggregated_bookings`** – Aggregated booking data by date and room type.  
5. **`fact_bookings`** – Detailed booking transactions, including revenue and ratings.
---

## Column Descriptions  

### `dim_date`  
- **`date`**: Dates in May, June, and July.  
- **`mmm yy`**: Date format as "Month Year" (e.g., May 2023).  
- **`week no`**: Unique week number for the date.  
- **`day_type`**: Indicates if the day is a weekend or weekday.  

### `dim_hotels`  
- **`property_id`**: Unique ID for each hotel.  
- **`property_name`**: Name of the hotel.  
- **`category`**: Classification of the hotel (Luxury, Business).  
- **`city`**: City where the hotel is located.  

### `dim_rooms`  
- **`room_id`**: Room type (RT1, RT2, RT3, RT4).  
- **`room_class`**: Class of the room (Standard, Elite, Premium, Presidential).  

### `fact_aggregated_bookings`  
- **`property_id`**: Unique ID for each hotel.  
- **`check_in_date`**: Customer check-in date.  
- **`room_category`**: Room type booked.  
- **`successful_bookings`**: Count of successful bookings for a room type on a date.  
- **`capacity`**: Maximum available rooms for a room type on a date.  

### `fact_bookings`  
- **`booking_id`**: Unique ID for each booking.  
- **`property_id`**: Unique ID for each hotel.  
- **`booking_date`**: Date of booking.  
- **`check_in_date`**: Date of check-in.  
- **`check_out_date`**: Date of check-out.  
- **`no_guests`**: Number of guests per booking.  
- **`room_category`**: Room type booked.  
- **`booking_platform`**: Booking platform used (e.g., OTA, Direct).  
- **`ratings_given`**: Customer ratings for hotel services.  
- **`booking_status`**: Status of the booking (Cancelled, Checked Out, No Show).  
- **`revenue_generated`**: Total revenue from the booking.  
- **`revenue_realized`**: Final revenue after considering cancellations and no-shows.  

---

## Key Insights from the Hotel Booking Analysis Project 🏨📊  

### 1. Room Category Performance  
- **RT4 Dominance:** Room Type RT4 emerged as the most frequently booked category, contributing significantly to overall revenue.  
- **Optimization Opportunities:** Uneven demand across room categories suggests the potential for optimizing pricing and marketing for underbooked types.  

---  

### 2. Booking Platform Analysis  
- **Revenue Concentration:** A few platforms dominated the revenue share, underlining their importance.  
- **Underutilized Platforms:** Lesser-used platforms could benefit from targeted promotions or partnerships to boost performance.  

---  

### 3. Hotel Category Insights  
- **Revenue Hierarchy:** Luxury hotels led in revenue generation, followed by premium and standard categories.  
- **City-Specific Performance:** Occupancy rates varied by category, with distinct city-specific strengths, guiding strategic focus.  

---  

### 4. Revenue Trends  
- **Seasonal Patterns:** Monthly revenue analysis revealed significant seasonal peaks, especially around holidays and vacations.  
- **Outlier Analysis:** Identifying high and low revenue outliers provides opportunities for investigating and replicating successful strategies.  

---  

### 5. City-Specific Occupancy and Revenue  
- **High-Demand Cities:** Certain cities demonstrated consistently high occupancy, indicating robust demand.  
- **Strategic Allocation:** City-based trends can inform investment, marketing, and resource allocation decisions.  

---  

### 6. Occupancy Rate Insights  
- **Category Dynamics:** Standard and premium rooms had higher occupancy rates compared to economy rooms.  
- **Urban Centers:** Urban hotels experienced the highest occupancy rates, correlating with elevated revenue figures.  

---  

### 7. Customer Ratings  
- **City Variance:** Significant differences in customer ratings across cities suggest opportunities for targeted quality improvements.  
- **Enhancing Satisfaction:** Low-rating locations could benefit from focused efforts to improve guest experiences.  

---  

### 8. Revenue by Booking Platform  
- **Dominant Channels:** Direct Bookings and Online Travel Agencies (OTAs) were major revenue contributors.  
- **Strategic Partnerships:** Strengthening relationships with top-performing OTAs is crucial for sustained growth.  

---  

### 9. Revenue by Hotel Category  
- **Luxury Focus:** Luxury and premium hotels accounted for a large share of the revenue, highlighting them as key profitability drivers.  
- **Targeted Marketing:** Enhanced marketing and operational efficiency in these categories could maximize returns.  

---  

### 10. Data Quality Observations  
    - **Outliers and Anomalies:** Preprocessing steps, such as removing bookings with zero guests or revenue outliers, improved data reliability.  
  - **Missing Data Handling:** Median imputation for missing values (e.g., room capacities) ensured robust analysis.  
---  
## Recommendations Based on Insights 🌟📋  

1. **Enhance Pricing Strategies**  
   - Implement dynamic pricing models to capitalize on high-demand months and optimize revenue.  
   - Adjust pricing for underbooked room categories to improve occupancy and profitability.  

2. **Optimize Booking Platforms**  
   - Incentivize high-performing platforms (e.g., OTAs, Direct Booking) to maintain their dominance in revenue share.  
   - Explore partnerships and promotional strategies with lesser-utilized platforms to reach untapped customer segments.  

3. **Improve Low-Rating Locations**  
   - Prioritize cities or properties with lower customer ratings for targeted quality enhancements, such as training staff, upgrading facilities, or addressing common complaints.  
   - Conduct surveys to identify key drivers of dissatisfaction and take corrective actions.  

4. **Seasonal Marketing Campaigns**  
   - Develop and execute promotional campaigns during historically low-revenue months to stabilize demand.  
   - Align campaigns with local or global events to attract more bookings during off-peak seasons.  

5. **Invest in High-Performing Locations**  
   - Expand operations in cities with high occupancy and revenue trends to capture more market share.  
   - Assess opportunities for opening new properties or scaling existing ones in high-demand areas.  
---
