Aviation Risk Analysis Project (Phase 1)

This project analyzes aviation accident data to identify the safest aircraft types for purchase and operation. Through exploratory data analysis (EDA), visualizations, and business‑oriented recommendations, it supports strategic decisions for a company planning to enter the aviation industry.

---

Business Understanding

Stakeholder: Head of the Aviation Division  
Business Problem: Our company is expanding into aviation but lacks expertise on accident trends and high‑risk aircraft. We must identify aircraft makes and flight operations with the lowest safety risk to guide investment decisions.  
Key Questions:
- How have aviation accident rates and injury totals changed over time?
- Which aircraft makes are linked to the most severe accidents?
- What flight phases, weather conditions, and purposes carry highest risk?



Data Understanding & Preparation

- Source: NTSB civil aviation accident dataset (1948–2007)  
- Records Analyzed: ~60,000 accident records  
- Key Features:  
  - `event_year`, `broad_phase_of_flight`, `weather_condition`, `purpose_of_flight`  
  - `make` (aircraft manufacturer)  
  - Injury counts: `total_fatal_injuries`, `total_serious_injuries`, `total_minor_injuries`, `total_uninjured`  
- Cleaning Steps:  
  1. Standardized column names (lowercase, underscores)  
  2. Filled missing injury values with 0, dropped rows missing critical fields  
  3. Converted dates to datetime, extracted `event_year`  
  4. Created `total_injuries` = sum of all injury types  


 Key Visualizations

All 14 charts are in the `visuals/` folder. Highlights include:

1. Accidents Over Time – line chart of accidents per year  
2. Total Injuries Over Time – line chart of injuries per year  
3. Accidents by Flight Phase – bar chart of accident counts by phase  
4. Injuries by Flight Phase – bar chart of total injuries by phase  
5. Accidents by Weather Condition – VMC vs IMC comparison  
6. Accidents & Injuries by Flight Purpose** – frequency and severity  
7. Fatal Injuries by Aircraft Make – top 10 manufacturers  
8. Accident Counts by Aircraft Make – top 10 manufacturers  
9. Avg. Injuries per Accident by Flight Purpose – severity per event  
10. Injury Distribution & Outliers – box plot per year  
11. Survivability Analysis – scatter of uninjured vs injuries  
12. Stacked Injury Types by Phase – fatal/serious/minor breakdown  

These visuals support our final recommendations.

Results & Recommendations

1. Invest in Beechcraft – lowest fatality and injury rates, versatile for corporate and utility operations.  
2. Avoid high‑risk segments(Personal and Unknown flight purposes) and high‑fatality makes (e.g., certain Piper and experimental models).  
3. Strengthen safety in landing/takeoff phase* and during clear‑weather operations (VMC), where most injuries occur—focus training and equipment there.

---

Future Work

- Incorporate post‑2007 data and international records  
- Add aircraft age, maintenance logs, and pilot experience  
- Explore predictive models for accident likelihood  


