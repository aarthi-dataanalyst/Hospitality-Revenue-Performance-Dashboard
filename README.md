
# 🏨 Hotel Booking Analysis using Power BI

This Power BI dashboard project analyzes hospitality revenue and hotel booking performance for a fictional hotel chain, **Atliq Hotels**, over a period of time. The goal is to uncover key insights on revenue trends, occupancy, booking behavior, and platform performance.

---

## 📌 Objective

To build a comprehensive and interactive Power BI dashboard that:
- Tracks hotel performance using KPIs like **Revenue, RevPAR, ADR, DSRN, Occupancy%, Realisation%**
- Compares **weekdays vs weekends** booking behavior
- Visualizes trends across **city, room type, platform, and time**
- Reveals actionable business insights with tooltip pages and WoW % indicators

---

## 📁 Dataset

The data was taken from a guided project and includes:
- Hotel properties and city
- Booking details like revenue, occupancy, booking source, room nights
- Date-based attributes

---

## 🧱 Project Workflow

1. **Data Source**: CSV files
2. **Data Transformation**: Performed in **Power Query**
   - Cleaned data
   - Added calculated columns for custom insights
3. **Data Modeling**:
   - Implemented **star schema**
   - Created relationships between fact and dimension tables
4. **DAX Calculations**:
   - Created calculated columns (`Week Number`, `Day Type`)
   - Created measures for KPIs and **WoW % (Week-over-Week Change)**

5. **Dashboarding**:
   - **Page 1: Executive Overview**
     - KPI cards with conditional icons (up/down)
     - Line chart for key metrics
     - Revenue by category and property
     - Tooltip page for weekly and day type breakdowns
   - **Page 2: Drill-down Analysis**
     - Revenue, occupancy, ratings by city and property
     - Booking % by room class, platform, and day type
     - Cancellation % analysis

---

## 📊 Key Features

- ✅ Week Number (`WEEKNUM`) & Day Type using DAX logic
- ✅ Conditional formatting with arrows for WoW %
- ✅ Interactive slicers by **City, Room Type, Property, Date**
- ✅ Tooltips based on **Week Number & Day Type**
- ✅ Clean & professional design with navigation buttons and icons

---

## 💡 Business Insights

- **Direct booking** has lower cancellation % than OTA
- **Elite room class** has high ADR but low occupancy
- **Delhi** has high rating but lower occupancy → opportunity for local promotion
- **Mumbai** brings the highest revenue → test premium pricing
- **Hyderabad** shows weekday-only demand → offer weekend packages

---

## 🛠 Tools Used

- Power BI
- Power Query
- DAX

---

## 📌 Conclusion

This project showcases my ability to apply Power BI for real-world business problems by combining data cleaning, modeling, visual storytelling, and business insights.

---

## 🔗 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://linkedin.com/)  
[![GitHub](https://img.shields.io/badge/GitHub-black?logo=github)](https://github.com/)

