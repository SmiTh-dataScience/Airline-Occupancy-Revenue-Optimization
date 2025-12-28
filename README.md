# Airline Occupancy & Revenue Optimization Analytics

This project analyzes airline operational data to identify opportunities to improve revenue
by increasing seat occupancy on underutilized aircraft.

The analysis focuses on fleet utilization, fare mix, and revenue efficiency using SQL and Python,
with an emphasis on realistic airline KPIs and decision-making under cost pressure.

---

## 📌 Business Problem
Airlines operate under increasing cost pressure due to fuel prices, labor costs,
regulatory constraints, and taxation. Adding new aircraft is expensive, so improving
revenue through better utilization of existing capacity becomes critical.

This project aims to:
- Identify underutilized aircraft
- Analyze occupancy and revenue per seat
- Quantify potential revenue uplift from improved occupancy

---

## 📊 Dataset Overview
The analysis uses an airline operations database containing:
- Flights and aircraft information
- Seat configurations
- Ticket bookings and fares
- Boarding data (actual boarded passengers)

Key tables:
- `flights`
- `seats`
- `ticket_flights`
- `boarding_passes`
- `bookings`
- `tickets`

---

## 🛠 Tools & Technologies
- **SQL (SQLite)** — data extraction, joins, aggregations
- **Python** — pandas, matplotlib, seaborn
- **Jupyter Notebook** — analysis and visualization

---

## 🔍 Analysis Approach
1. Validated data quality across all tables
2. Analyzed fleet capacity by aircraft type
3. Studied booking and revenue trends over time
4. Calculated average ticket prices by aircraft and fare class
5. Measured occupancy using boarded passengers vs total seats
6. Simulated a 10% increase in occupancy to assess revenue impact

---

## 📈 Key Metrics Used
- Occupancy rate (booked seats / total seats)
- Revenue per ticket
- Fare mix by aircraft
- Total revenue by aircraft type

---

## 💡 Key Insights
- Occupancy and revenue performance vary significantly by aircraft type
- Business fares consistently generate higher revenue, but some aircraft rely on volume
- Several aircraft show revenue leakage due to unused seat capacity
- Improving occupancy on existing flights can meaningfully increase revenue

---

## 📉 Revenue Impact Simulation
A scenario analysis was performed assuming a **10% increase in occupancy**
across aircraft types. The simulation showed a clear uplift in total annual revenue,
highlighting occupancy optimization as a high-impact, low-cost lever.

> Note: This is a sensitivity analysis, not a production forecast.

---

## 📌 Recommendations
- Focus on occupancy and pricing optimization for underperforming aircraft
- Improve fare mix rather than applying blanket price reductions
- Prioritize revenue per seat over fleet expansion under cost constraints

---

## 🚧 Limitations
- No competitor pricing or market demand data
- No route-level or time-of-day segmentation
- Analysis is exploratory and not deployed in production

---

## 🧠 What This Project Demonstrates
- Understanding of airline economics and capacity utilization
- Strong SQL-driven analytical thinking
- Ability to translate data into business-relevant insights
- Clear, defensible reasoning suitable for real-world analytics roles

---

## 📁 Repository Structure


---

##
Smit Solanki  
Data Analyst | Airline & Operations Analytics  

