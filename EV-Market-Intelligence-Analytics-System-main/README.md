# 🚗 EV Market Intelligence & Analytics System

## 📌 Overview
The **EV Market Intelligence & Analytics System** is an end-to-end business intelligence solution built using Power BI to analyze trends, performance, and market dynamics within the global electric vehicle (EV) industry. The project transforms raw EV market data into a structured analytical model and interactive dashboards that support executive decision-making and strategic analysis.

The system combines data modeling, ETL, and visualization to deliver actionable insights into manufacturer performance, battery technologies, charging standards, pricing, and future market growth.

---

## 🎯 Objectives
- Create a unified analytical view of the global EV market  
- Enable comparison across manufacturers, technologies, and regions  
- Surface key performance indicators (KPIs) and trends  
- Support data-driven decision making through interactive dashboards  

---

## 🏗️ Architecture & Data Modeling
- Designed a **Power BI–native data mart** using a **star schema**
- Implemented ETL using **Power Query**
- Built reusable analytical logic using **DAX measures**
- Central **FactEV** table connected to dimension tables:
  - Manufacturer
  - Model
  - Battery
  - Charging
  - Country
  - Time
  - Technology
- Enforced **many-to-one relationships**, single-direction filtering, and no many-to-many ambiguity

---

## 📊 Dashboards & Analysis
The system includes four interactive dashboards:

1. **Market Overview**
   - Sales trends, total revenue, top manufacturers, and geographic distribution

2. **Technology & Performance Analysis**
   - Battery range, charging efficiency, and performance benchmarks

3. **Market Forecast & Financial Insights**
   - Revenue analysis, sales correlation, and multi-year forecasts

4. **Consumer & Vehicle Insights**
   - Price vs. range positioning, safety ratings, and warranty comparisons

Each dashboard is designed to answer a specific analytical question while maintaining executive-level clarity.

---

## 📈 Key Insights
- Certain manufacturers consistently lead in unit sales and revenue
- Lithium-based battery technologies dominate market adoption
- Higher battery capacity generally correlates with increased driving range
- Charging speed varies significantly across charging standards
- Forecasts indicate continued growth in EV adoption over the next three years

---

## 🛠️ Tools & Technologies
- **Power BI**
- **Power Query (ETL)**
- **DAX**
- **Star Schema Data Modeling**
- **Interactive Dashboards & Forecasting**

---

## 💡 Business Impact
- Consolidated complex EV market data into a single analytical system
- Reduced reliance on manual analysis through standardized KPIs and dashboards
- Improved visibility into market trends, performance drivers, and technology adoption

---

## 🚀 Future Enhancements
- Automate data refresh for near real-time insights
- Integrate external datasets such as charging infrastructure and policy incentives
- Expand forecasting using advanced predictive models

---

## 📁 Repository Contents
- Power BI report (`.pbix`)
- Dashboard screenshots
- Project documentation

---

## 👤 Author
**Omkar Chougule**

