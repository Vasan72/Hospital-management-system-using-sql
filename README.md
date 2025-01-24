# Hospitality Dashboard Project

This repository contains the Power BI Hospitality Dashboard project, which provides insights into hotel bookings, customer behavior, and revenue analysis using multiple datasets. The project uses five CSV files to analyze key metrics and generate meaningful visualizations.

---

## 📁 Data Files Overview
The project utilizes the following CSV files:
1. **dim_date**: Contains information about dates and their attributes.
2. **dim_hotels**: Provides details about hotels and their properties.
3. **dim_rooms**: Specifies the types and classes of rooms available in hotels.
4. **fact_aggregated_bookings**: Summarizes bookings with aggregated statistics.
5. **fact_bookings**: Details individual customer bookings and related metrics.

---

### 📊 Column Descriptions

#### **dim_date**
- **date**: Dates within May, June, and July.
- **mmm yy**: Month and year in the format (e.g., "May 23").
- **week no**: Unique week number for each date.
- **day_type**: Categorizes days as Weekend or Weekday.

#### **dim_hotels**
- **property_id**: Unique identifier for each hotel.
- **property_name**: Name of the hotel.
- **category**: Class of the hotel (Luxury or Business).
- **city**: City where the hotel is located.

#### **dim_rooms**
- **room_id**: Room type (e.g., RT1, RT2, RT3, RT4).
- **room_class**: Class of the room (e.g., Standard, Elite, Premium, Presidential).

#### **fact_aggregated_bookings**
- **property_id**: Unique identifier for hotels.
- **check_in_date**: Check-in dates for customers.
- **room_category**: Room type.
- **successful_bookings**: Number of successful room bookings for a given date.
- **capacity**: Maximum rooms available for a specific room type.

#### **fact_bookings**
- **booking_id**: Unique ID for each customer booking.
- **property_id**: Unique identifier for hotels.
- **booking_date**: Date the customer booked their room.
- **check_in_date**: Date the customer checked into the hotel.
- **check_out_date**: Date the customer checked out of the hotel.
- **no_guests**: Number of guests in the booking.
- **room_category**: Room type booked by the customer.
- **booking_platform**: Booking platform used by the customer.
- **ratings_given**: Ratings provided by the customer.
- **booking_status**: Status of the booking (Cancelled, Checked Out, No Show).
- **revenue_generated**: Gross revenue from the customer.
- **revenue_realized**: Final revenue after accounting for booking status.

---

## 📌 Project Highlights
- **Tools Used**: Power BI for dashboard creation and data visualization.
- **Key Insights**: 
  - Booking trends over time.
  - Revenue analysis by hotel and room type.
  - Guest preferences and booking platforms.
  - Hotel performance metrics based on ratings and revenue.

---

## 🚀 How to Use
1. Clone this repository.
2. Load the provided datasets into Power BI.
3. Explore the pre-built dashboard for insights.
4. Use the meta information to customize or extend the analysis.

---

## 🌟 Features
- **Dynamic Visualizations**: Interactive charts and graphs to analyze data effectively.
- **Detailed Analysis**: Drill-down capabilities for better decision-making.
- **Revenue Breakdown**: Insights into gross and net revenue for hotels.

---

## 📚 Future Work
- Enhance visualizations by incorporating additional metrics.
- Include predictive analytics for future booking trends.
- Automate data updates using APIs or scheduled scripts.

---

## 📝 License
This project is licensed under the MIT License.

---

## 📬 Contact
For queries or collaboration opportunities, feel free to reach out!
