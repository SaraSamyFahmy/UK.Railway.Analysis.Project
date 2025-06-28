# UK.Railway.Analysis.Project
Built a railway database using SQL with tables for stations, routes, calendars, journeys, and transactions. Used Python and Excel for data cleaning, and Tableau for visualizing route usage, journey trends, and transaction insights.

---

## 🚄 Overview

This project was completed as part of the **Digital Egypt Pioneers Initiative (DEPI)** under the **Google Data Analytics Specialist Track**. It represents a full end-to-end data analytics pipeline, starting from raw data ingestion and relational modeling to interactive dashboards and time series forecasting.

---

## 🔧 Tools & Technologies

- **Excel** – Early-stage validation and formatting
- - **Python** – Data cleaning, feature engineering, forecasting  
- **SQL** – Schema design, normalization, querying  
- **Tableau / Power BI** – Dashboarding and storytelling  
- **Prophet & Random Forest** – Time series modeling

---

## 🗂️ Project Structure

UK-Railway-Analysis/
└── README.md # Project overview
├── dataset/ # Raw source files
├── documentation/ # Project report and supporting docs
├── presentation/ # Final presentation slides
├── excel/ # Cleaned data (Excel)
├── sql/ # Database schema & queries
├── python/ # Analysis and preprocessing notebooks
├── Tableau/ # Tableau dashboards
├── forecasting/ # Forecasting models & evaluation

---

## 🧱 Data Modeling & Engineering

- **Validation**: Checked for missing values, formatting issues, duplicates  
- **Cleaning**: Standardized categories (e.g., `"None"` → `"No Railcard"`), fixed station names, formatted date/time  
- **Feature Engineering**: Created route codes, delay categories, date types  
- **Normalization**: Structured the database into 5 main tables:
  - `Stations`, `Routes`, `Journeys`, `Transactions`, `Calendar`
- **Schema Design**: Built relational structure with foreign key constraints

---

## 📊 Key Analysis Insights

### 🎟️ Passenger Behavior
- Most popular ticket type: **Advance**  
- Over **90%** of passengers travel Standard Class  
- **58.5%** of purchases made online  
- **33.9%** used a Railcard  
- Top payment method: **Credit Card (60%)**

### 🚉 Journey Performance
- **19,871** total journeys  
- **18,019** on-time (90.7%)  
- **1,062** delayed, **790** cancelled  
- Average delay duration: **37 minutes**  
- Top delay causes: **Weather**, **Staff Shortage**

### 🗺️ Network & Routes
- **64** unique routes  
- **12** departure stations, **31** arrival stations  
- Busiest departure: **Manchester Piccadilly**  
- Busiest arrival: **Birmingham New Street**  
- Highest delay rates: **YRK–WKF**, **EUS–YRK**, **EDB–KGX**

### 💰 Financial Overview
- **Total revenue**: £741,921  
- **Net revenue** after refunds: £703,219  
- Most profitable route: **KGX–YRK**  
- Advance ticket sales: **£293,600**

---

## 🔮 Forecasting Results (May 2024)

Using **Prophet** and **Random Forest Regressor**, the following were forecasted for May 2024:

| Metric        | Forecast      |
|---------------|---------------|
| Bookings      | 8,147         |
| Journeys      | 5,100         |
| First Class   | 800 tickets   |
| Revenue       | £195,457      |
| MAPE Accuracy | ~8–11%        |

Seasonal trends and holidays were modeled using calendar-based features.

---

## 🧠 Recommendations

- **Peak Hours**: Increase staffing, reduce headway, apply real-time tracking  
- **High Delay Routes**: Audit schedules, staff availability, and route conditions  
- **Refund Policy**: Offer tiered compensation (e.g., 25%, 50%, 100%) for delays  
- **Holidays**: Maintain current frequency due to low demand trends

---

## 👥 Team

- **Supervisor**: Eng. Ahmed Samir  
- **Team Members**: Ahmed Saad, George Ayad, Dina Sherif, Marwa Adel, Sara Samy, Hoda Gamal

---

## 📬 Contact

**Ahmed Saad El Fiky**  
📧 [Mail](sara.samy.fahmy2@gmail.com)  
🔗 [Linkedin]([https://linkedin.com/in/SaadFiky](https://www.linkedin.com/in/sarasamyfahmy/))

---

## ✅ Project Status

- ✅ Data Cleaning & Preprocessing  
- ✅ Relational DB Design  
- ✅ Dashboards Completed (Tableau & Power BI)  
- ✅ Forecasting Models  
- ✅ Final Report & Presentation Delivered
