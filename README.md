# 🏨 OYO Rooms – Hotel Analytics Dashboard

![Domain](https://img.shields.io/badge/Domain-Hospitality%20Analytics-blue?style=for-the-badge)

---

## 📌 Project Overview

An end-to-end **Power BI dashboard** analyzing OYO Rooms' hotel operations across key business dimensions — revenue performance, hotel-level metrics, and booking channel behaviour. The report surfaces actionable insights for hospitality managers and business analysts to optimize occupancy, pricing strategy, and customer acquisition channels.

---

## Dashboard Overview

-[View Dashboard](https://github.com/Ayushipundir-cloud/Hotel-Booking-Analytics-OYO/blob/main/Sales%20Overview.png)
-[View Dashboard](https://github.com/Ayushipundir-cloud/Hotel-Booking-Analytics-OYO/blob/main/Hotel%20Performance.png)
-[View Dashboard](https://github.com/Ayushipundir-cloud/Hotel-Booking-Analytics-OYO/blob/main/Hotel%20Performance.png)

## 🎯 Business Objectives

- Track overall revenue, bookings, and occupancy across cities and states
- Measure hotel-level performance using industry KPIs (ADR, RevPAR, Occupancy %)
- Understand booking patterns across channels, customer types, and room categories
- Enable slice-and-dice analysis by time (quarter, month, season), geography, and property type

---

## 📊 Dashboard Pages

### 1. Sales Overview
High-level snapshot of business performance with KPI cards and trend analysis.

- Total Revenue, Total Bookings, Occupancy %, ADR, RevPAR, Avg Nights Stayed
- Revenue breakdown by city and quarter (Pivot Table)
- Trend charts across months and seasons
- Slicers for state, city, quarter, and month

### 2. Hotel Performance
Deep dive into individual hotel and property-type performance.

- Hotel-wise comparison of key metrics
- Property type segmentation (budget, premium, etc.)
- Geographic performance across states and cities
- Room type contribution analysis

### 3. Booking Channel Analysis
Understanding how customers book and pay.

- Market segment breakdown (corporate, leisure, online, etc.)
- Customer type analysis (new vs. returning)
- Payment method distribution
- Channel-wise revenue and booking volume

---

## 🗂️ Data Model

The report follows a **Star Schema** design with one fact table and multiple dimension tables:

| Table | Type | Description |
|---|---|---|
| `Fact_Bookings` | Fact | Core booking transactions |
| `Dim_Hotels` | Dimension | Hotel and property attributes |
| `Dim_Rooms` | Dimension | Room type details |
| `Dim_Customers` | Dimension | Customer profile and type |
| `Dim_Date` | Dimension | Date hierarchy (day, month, quarter, season) |
| `Customer RFM` | Calculated | RFM-based customer segmentation |

---

## 📐 Key Measures (DAX)

| Measure | Description |
|---|---|
| `Total Revenue` | Sum of all booking revenue |
| `Total Bookings` | Count of booking transactions |
| `Occupancy %` | Rooms occupied / total available rooms |
| `ADR` | Average Daily Rate per occupied room |
| `RevPAR` | Revenue Per Available Room |
| `Avg Nights Stayed` | Average length of stay per booking |

---

## 🔍 Visual Types Used

`Card` · `Area Chart` · `Clustered Bar Chart` · `Clustered Column Chart` · `Donut Chart` · `Pie Chart` · `100% Stacked Bar Chart` · `Pivot Table` · `Slicer` · `Table`

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard development |
| DAX | Custom measures and RFM segmentation |
| Power Query (M) | Data cleaning and transformation |
| Star Schema | Data modelling |

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `Oyo_Dashboard.pbix` in **Power BI Desktop** (free download from Microsoft)
3. If prompted, update the data source path to match your local setup
4. Explore the three report pages using the slicers and filters

> **Note:** This dashboard was built using sample/synthetic hospitality data for analytical and portfolio purposes.

---

## 👩‍💻 Author

**Ayushi Pundir**
Junior Data Analyst | Bengaluru, India

[![GitHub](https://img.shields.io/badge/GitHub-Ayushipundir--cloud-181717?style=flat&logo=github)](https://github.com/Ayushipundir-cloud)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/)

---

*Part of my data analytics portfolio. Feel free to fork, explore, and share feedback!*
