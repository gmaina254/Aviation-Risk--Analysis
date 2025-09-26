# Aviation Accident Data Analysis (1962–2023)

## 📌 Project Overview
This project analyzes **80,000+ aviation accident records (1962–2023)** from the National Transportation Safety Board (NTSB).  
The business case: a company expanding into the aviation industry needs to understand **which aircraft types, flight operations, and conditions are safest** to minimize investment risks.  

The project applies **data cleaning, exploratory data analysis (EDA), and visualization** to uncover accident trends, risk factors, and safety insights.  

---

## 🎯 Objectives
- Identify low-risk aircraft types and flight operations.  
- Assess how weather, flight phase, and flight purpose affect accident frequency and severity.  
- Deliver **three actionable recommendations** to guide aviation investment and operational decisions.  

---

## 🛠️ Tools & Technologies
- **Python** (pandas, NumPy, matplotlib, seaborn)  
- **Jupyter Notebook**  
- **Data Source:** NTSB Aviation Accident Database  

---


---

## 🔍 Key Steps
1. **Data Cleaning & Preparation**
   - Standardized column names, selected relevant features, and handled missing values.  
   - Created new features: `event_year`, `total_injuries`.  
   - Cleaned 90k+ rows for consistency.  

2. **Exploratory Data Analysis (EDA)**
   - Accident & injury trends over time.  
   - Accident frequency by **flight phase, weather conditions, and purpose of flight**.  
   - Severity analysis (fatal, serious, minor injuries).  
   - Accident counts by **aircraft manufacturer**.  

3. **Visualization**
   - Line charts: accident & injury trends (1948–2023).  
   - Bar charts: accidents & injuries by phase of flight, weather, and aircraft type.  
   - Box plots & scatter plots to detect **outliers and severity distributions**.  

---

## 📊 Key Insights
- **Most accidents occur during good weather (VMC)** → human/technical errors outweigh weather.  
- **Cruise phase has the deadliest accidents** despite being considered the “safest” phase.  
- **Takeoff & landing are high-frequency accident phases** → critical areas for pilot training.  
- **Personal flights dominate accident counts and injuries** → a riskier investment segment.  
- **Cessna & Piper aircraft account for the most fatal injuries** historically.  

---

## ✅ Recommendations
1. **Avoid investing heavily in personal or instructional flight operations** → focus on business/commercial segments.  
2. **Prioritize pilot training in takeoff, cruise, and landing phases** to reduce risk exposure.  
3. **Select aircraft manufacturers with strong safety records** (avoid those with historically high fatalities like Cessna & Piper).  

---

