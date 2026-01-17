# ✈️ Flight Status Dashboard — PB15 .

## 📌 Project Overview  
This project analyzes **flight operations data** using **Power BI**, with the objective of understanding **flight performance by status (on-time, delayed, canceled), airline contribution, airport volume, and cancellation causes**.  

The dashboard is designed to showcase **data visualization, exploratory analysis, and business storytelling skills**, using real-world aviation data — perfect for demonstrating operational insight in the transportation and logistics sector.

---

## 👀 Dashboard Preview  
<img width="596" height="329" alt="Flight Status Dashboard -PB15" src="https://github.com/user-attachments/assets/458ce24e-030d-4fee-be7e-cfdcf2299c3c" />

*(Screenshot captured January 17, 2026)*

---

## 🎯 Objectives  
- Analyze **total flights, delayed flights, and canceled flights**  
- Compare **flight volume by major U.S. airports**  
- Understand **delay rates by airline carrier**  
- Visualize **cancellation causes (weather, airline, national air system)**  
- Explore **overall flight status distribution**  
- Practice **dashboard design and analytical storytelling** in Power BI

---

## 📊 Dashboard Breakdown

### 🔹 Key Metrics (KPIs)
- **Total Flights**: 1.9M  
- **Delayed Flights**: 791.6K (40.6%)  
- **Canceled Flights**: 28.6K (1.5%)  
→ Highlights **significant delay rate**, but low cancellation rate

---

### 🔹 Total Flights by Airport
- Horizontal bar chart showing top U.S. airports:  
  - Atlanta: **346,836**  
  - Chicago: **285,884**  
  - Dallas-Fort Worth: **239,551**  
  - Denver: **196,055**  
  - Los Angeles: **194,673**  
  - San Francisco: **148,008**  
  - Phoenix: **146,815**  
  - Houston: **146,622**  
  - Las Vegas: **133,181**  
  - Minneapolis: **112,117**  
→ Confirms **Atlanta as busiest hub**, followed by Chicago and DFW

---

### 🔹 Delayed Flights by Airline
- Horizontal bar chart showing delay rates per carrier:  
  - United Airlines: **53.5%**  
  - Southwest Airlines: **51.4%**  
  - Spirit Airlines: **49.2%**  
  - JetBlue Airways: **44.3%**  
  - Frontier Airlines: **40.7%**  
  - Virgin America: **39.4%**  
  - American Airlines: **37.7%**  
  - American Eagle: **37.1%**  
  - Delta Air Lines: **35.7%**  
  - Skywest Airlines: **35.0%**  
  - Atlantic Southeast: **32.8%**  
  - US Airways Inc.: **31.2%**  
  - Alaska Airlines: **24.5%**  
  - Hawaiian Airlines: **24.2%**  
→ Reveals **United and Southwest have highest delay rates**, while **Alaska and Hawaiian are most reliable**

---

### 🔹 Canceled Flights — Causes
- Donut chart showing:  
  - **Weather**: ~50% (large turquoise slice)  
  - **Airline/Carrier**: ~30% (dark gray)  
  - **National Air System**: ~20% (light gray)  
→ Confirms **weather as primary cause of cancellations**

- Bar chart below shows **cancellation rate by day of week** (2=Monday → 6=Friday):  
  - Monday: **2.3%**  
  - Tuesday: **1.4%**  
  - Wednesday: **1.2%**  
  - Thursday: **1.3%**  
  - Friday: **1.0%**  
  - Saturday: **1.7%**  
→ Suggests **higher cancellations at start/end of week** — possibly due to scheduling or weather patterns

---

### 🔹 Flight Status Distribution
- Progress bar + percentage breakdown:  
  - **On-Time**: 58.0%  
  - **Delayed**: 40.6%  
  - **Canceled**: 1.5%  
→ Shows **majority of flights operate on schedule**, but delays are still very common

---

## 📐 Methodology
- Data cleaning and preprocessing (handling missing values, standardizing airline/airport names)  
- Creation of calculated measures:  
  - `Delayed % = DIVIDE([Delayed Flights], [Total Flights])`  
  - `Cancellation Cause % = CALCULATE(COUNTROWS(Flights), FILTER(Flights, Flights[Cause] = "Weather")) / [Total Flights]`  
- Use of:  
  - KPI cards  
  - Bar charts  
  - Donut charts  
  - Progress bars  
  - Filters (if applicable)  
- Focus on **visual consistency, readability, and dark theme with yellow/cyan accents**

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**  
- **Data modeling** (star schema implied)  
- **Basic–Intermediate DAX** (aggregations, percentages, conditional logic)  
- **Data visualization principles** (color theory, spacing, hierarchy)  
- **Dashboard layout & storytelling** (flow from overview → deep dive into delays & cancellations)

---

## 📌 Key Insights
✅ **1.9M total flights analyzed** — large-scale dataset representing major U.S. carriers  
✅ **40.6% of flights delayed** — high operational volatility, especially for United & Southwest  
✅ **Only 1.5% canceled** — airlines prioritize rescheduling over cancellations  
✅ **Weather is #1 cause of cancellations** (~50%) — critical for risk management  
✅ **Atlanta is busiest airport** — key hub for network planning and resource allocation  
✅ **Alaska & Hawaiian Airlines show lowest delay rates** — potential benchmark for reliability  
✅ **Monday has highest cancellation rate (2.3%)** — plan accordingly for early-week disruptions


---

## 📁 Repository Structure

├── Flight_Status_Dashboard_PB15.pbix
├── Dataset/
│ └── flight_data.csv
├── Screenshots/
│ └── flight_status_dashboard_pb15.png
└── README.md


---

## 🚀 Project Purpose
This project was built as a **portfolio Power BI project** to:  
- Practice **aviation and logistics analytics**  
- Improve **dashboard design and visual storytelling**  
- Apply **business-oriented insight generation**  
- Simulate **analytics reporting for airlines, airports, or travel platforms**

---

## 📬 Contact
**Mustapha Tarfi**  
📍 Morocco  
🔗 LinkedIn: [https://www.linkedin.com/in/mustapha-tarfi-1106b5283/](https://www.linkedin.com/in/mustapha-tarfi-1106b5283/)  

---
