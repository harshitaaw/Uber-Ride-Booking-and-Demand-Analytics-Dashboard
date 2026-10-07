# 🚖 Uber Power BI Dashboard | Business Analytics Project

An end-to-end **Power BI business analytics project** designed to analyze ride-level data and generate actionable insights across **bookings, revenue, vehicle performance, customer behavior, cancellations, and locations**.

The project demonstrates practical skills in **data analysis, Power BI, DAX, Power Query, data modeling, time intelligence, KPI development, and dashboard design**.

---

## 📌 Project Overview

Ride-hailing businesses generate large volumes of transactional data across bookings, customers, vehicles, locations, payments, and cancellations.

This project transforms ride-level transactional data into an interactive Power BI dashboard that helps answer key business questions related to:

- Operational performance
- Revenue generation
- Vehicle utilization
- Customer behavior
- Cancellation and revenue loss
- Geographic demand
- Peak time patterns

The dashboard is designed from a **business decision-making perspective**, focusing not only on visualizing data but also on identifying performance trends, risks, and opportunities.

> **Dataset Note:** The original local dataset used during development was accidentally deleted. The dataset included in this repository is a **recreated synthetic ride-level dataset containing 150,000 records and 23 features**, structured to support the analysis and dashboard shown in this project. It is not Uber's proprietary internal data.

---

# 🎯 Business Objectives

The project focuses on the following business objectives:

- Monitor overall booking and revenue performance
- Identify major revenue-generating vehicle types
- Analyze vehicle-wise operational efficiency
- Measure ride completion and loss rates
- Understand customer behavior and loyalty
- Analyze customer cancellation patterns
- Estimate revenue impact from lost rides
- Identify high-demand pickup and drop locations
- Analyze peak demand time slots
- Compare monthly and quarterly performance
- Support data-driven operational and strategic decisions

---

# 📂 Dataset Overview

The recreated dataset contains:

- **150,000+ ride-level records**
- **23 analytical features**
- Date and time attributes
- Vehicle information
- Customer information
- Location information
- Revenue metrics
- Payment information
- Ratings
- Cancellation information
- Operational status indicators

### Main Dataset Fields

| Category | Fields |
|---|---|
| Booking | Booking ID, Booking Date, Booking Time, Booking Status |
| Vehicle | Vehicle Type |
| Customer | Customer ID, Customer Rating |
| Location | Pickup Location, Drop Location |
| Financial | Booking Value, Revenue, Lost Revenue |
| Distance | Distance KM |
| Payment | Payment Method |
| Driver | Driver Rating |
| Cancellation | Cancellation Reason, Incomplete Reason |
| Status Metrics | Completed Booking, Lost Booking |
| Time Intelligence | Month, Quarter, Day, Time Slot |

The complete field-level documentation is available in [`data_dictionary.csv`](data_dictionary.csv).

---

# 🧱 Dashboard Architecture

The dashboard is organized into five analytical pages:

1. **Overview**
2. **Vehicle Analysis**
3. **Revenue Analysis**
4. **Customer Analysis**
5. **Location Analysis**

Interactive navigation buttons, filters, KPIs, charts, tables, and trend visualizations allow users to move between different analytical areas.

---

# 📊 Dashboard Pages

## 1️⃣ Home / Landing Page

### Purpose

Provides an introduction to the project and acts as the main navigation page.

### Key Features

- Uber-inspired dashboard branding
- Project introduction
- Navigation to analytical pages
- Vehicle selection/navigation
- Clean dashboard layout

### Business Value

- Provides an intuitive user experience
- Establishes dashboard context
- Makes the report suitable for portfolio and stakeholder presentation

---

# 2️⃣ Overview Page

### Business Requirement

Provide an executive-level snapshot of overall operational and financial performance.

### Key Performance Indicators

- Total Bookings
- Lost Bookings
- Total Revenue
- Total Distance
- Average Distance per Ride

### Analysis

- Monthly booking trends
- Quarterly performance
- Monthly and quarterly distance trends
- Revenue by vehicle type
- Top pickup locations
- Top drop locations
- Peak time-slot performance
- Day-wise demand patterns

### Business Value

The overview page enables stakeholders to quickly understand overall business performance and identify areas requiring deeper investigation.

---

# 3️⃣ Vehicle Analysis

### Business Requirement

Analyze vehicle-level performance to understand fleet contribution and operational efficiency.

### Key Metrics

- Booking count by vehicle
- Revenue by vehicle type
- Revenue contribution %
- Completed bookings
- Lost bookings
- Ride completion rate
- Ride incomplete/lost rate
- Monthly booking trends

### Vehicle Types

- Auto
- Bike
- Go Mini
- Go Sedan
- Premier Sedan
- Uber XL

### Insights

The analysis helps identify:

- Highest revenue-generating vehicle types
- Vehicle contribution to overall revenue
- Differences in completion efficiency
- Monthly booking patterns
- Vehicle-level operational performance

### Business Value

Vehicle-level analysis can support:

- Fleet allocation
- Driver utilization
- Pricing decisions
- Incentive planning
- Operational optimization

---

# 4️⃣ Revenue Analysis

### Business Requirement

Analyze revenue performance and identify potential revenue risks.

### Key Analysis

- Monthly revenue trends
- Quarterly revenue trends
- Revenue by vehicle type
- Revenue by payment method
- Revenue by customer
- Revenue contribution
- Lost revenue

### Payment Methods

- UPI
- Cash
- Uber Wallet
- Credit Card
- Debit Card

### Efficiency Metrics

- Month-over-Month Revenue %
- Average Revenue per Booking
- Revenue per Kilometer
- Lost Revenue

### Business Value

Revenue analysis helps identify:

- Profitable vehicle segments
- Major revenue contributors
- Payment preferences
- Revenue leakage
- Revenue risk from cancelled/incomplete rides
- Financial performance trends

---

# 5️⃣ Customer Analysis

### Business Requirement

Understand customer behavior, loyalty, cancellation patterns, and revenue risk.

### Customer Segmentation

The analysis categorizes customers based on ride behavior:

- First-Time Customers
- Returning Customers
- Regular Customers

### Key Metrics

- Customer Cancellation Rate
- Customer Cancellation Count
- Customer Revenue Risk
- Lost Revenue Impact
- Customer Booking Trends

### Analysis

- Customer trend over time
- Payment method preferences
- Cancellation reasons
- Top customers by revenue
- Customer-level booking details

### Business Value

Customer analysis can help businesses:

- Improve customer retention
- Identify cancellation patterns
- Reduce revenue loss
- Understand customer preferences
- Improve overall customer experience

---

# 6️⃣ Location Analysis

### Business Requirement

Analyze geographic and time-based demand patterns to improve operational planning.

### Key Analysis

- Total distance by vehicle type
- Distance by location
- Top pickup areas
- Top drop areas
- Peak demand time slots
- Day-wise demand
- Time-slot heatmap

### Time Slots

The dashboard analyzes ride activity across operational time periods such as:

- Morning
- Afternoon
- Evening
- Night

### Business Value

Location and time analysis can support:

- Driver allocation
- Fleet positioning
- Demand planning
- Surge pricing decisions
- High-demand area identification
- City-level operational optimization

---

# 📈 Key Business KPIs

The dashboard uses DAX-based measures to calculate important business metrics including:

- Total Bookings
- Completed Bookings
- Lost Bookings
- Total Revenue
- Lost Revenue
- Total Distance
- Average Distance
- Average Revenue per Booking
- Revenue per Kilometer
- Completion Rate
- Lost Booking Rate
- Revenue Contribution %
- Month-over-Month Revenue Growth
- Customer Cancellation Rate

---
🚀 Future Enhancements
The project can be extended with advanced analytics capabilities such as:
- Real-time ride data integration
- Demand forecasting
- Customer churn prediction
- Driver performance analytics
- Predictive cancellation analysis
- Geographic demand forecasting
- Dynamic pricing analysis
- AI-powered business insights
- Automated Power BI Service refresh
- Advanced anomaly detection

📚 Key Learnings
Through this project, I developed practical experience in:
- End-to-end Power BI dashboard development
- Data cleaning and transformation using Power Query
- Creating DAX measures
- Data modeling and relationships
- Time-based analysis
- KPI development
- Business-oriented data analysis
- Customer segmentation
- Revenue analysis
- Operational performance analysis
- Data storytelling
- Dashboard UX and navigation
- Translating business requirements into analytical solutions

📊 Business Impact
The dashboard provides a consolidated view of ride operations and can help stakeholders:
- Track business performance
- Identify revenue growth opportunities
- Detect revenue loss areas
- Compare vehicle performance
- Improve fleet utilization
- Understand customer behavior
- Reduce cancellation-related losses
- Identify high-demand locations
- Understand peak operating periods
- Support data-driven decision-making

🛠 Tools & Technologies
Business Intelligence
- Microsoft Power BI
- Power BI Service / Microsoft Fabric
Data Analysis
- Power Query
- DAX
- Data Modeling
- Time Intelligence
Dashboard Development
- KPI Design
- Interactive Visualizations
- Dashboard UX
- Data Storytelling
- Drill-down and filtering
- Interactive Navigation
🔄 Project Workflow
The project follows an end-to-end analytics workflow:
Raw Ride-Level Data
        ↓
Data Cleaning & Transformation
        ↓
Power Query
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
KPI Development
        ↓
Interactive Visualizations
        ↓
Business Insights
        ↓
Power BI Dashboard



# 🧮 DAX & Analytics

The project uses **DAX (Data Analysis Expressions)** to create business measures and analytical calculations.

Example:

```DAX
Revenue =
SUM('Uber_Data'[Revenue])
Completion Rate
Completion Rate =
DIVIDE(
    [Completed Bookings],
    [Bookings],
    0
)

Average Revenue per Booking
Average Revenue per Booking =
DIVIDE(
    [Revenue],
    [Completed Bookings],
    0
)

Revenue per Kilometer
Revenue per KM =
DIVIDE(
    [Revenue],
    [Total Distance],
    0
)

# Revenue Contribution
Revenue Contribution % =
DIVIDE(
    [Revenue],
    CALCULATE(
        [Revenue],
        ALL('Uber_Data'[Vehicle_Type])
    ),
    0
)

These measures enable the dashboard to move beyond simple aggregation and provide business-oriented performance metrics.

<img width="1027" height="562" alt="Screenshot 2026-10-07 203212" src="https://github.com/user-attachments/assets/4f527098-07b6-4358-bf52-4777725dd642" />

