
# Identity Volatility Score – Aadhaar Stability Analysis

## Project Overview
The **Identity Volatility Score (IVS)** project introduces a novel, data-driven approach to assess the stability of Aadhaar identities across India. Aadhaar records often undergo post-enrolment demographic and biometric updates due to corrections, migration, or life events. While many updates are expected, unusually frequent updates in certain regions may indicate enrolment inaccuracies, administrative inefficiencies, or potential misuse.

This project defines a simple yet powerful metric to quantify such instability and visualizes it through an interactive Power BI dashboard for policy and operational decision-making.

---

## Problem Statement
There is currently no standardized metric to identify and compare regions where Aadhaar identities undergo frequent post-enrolment changes. Existing analyses rely on raw counts, which do not allow fair comparison across regions of different sizes.

---

## Proposed Solution
The project introduces the **Identity Volatility Score (IVS)**:

**IVS = (Total Demographic Updates + Total Biometric Updates) ÷ Total Enrolments**

The score provides a normalized indicator of Aadhaar identity stability:
- **High IVS** indicates frequent identity corrections and potential risk  
- **Low IVS** indicates stable and reliable enrolment outcomes  

---

## Datasets Used
The analysis is based on official UIDAI datasets:
- **Enrolment Dataset** – Aadhaar enrolments by age group and geography  
- **Demographic Update Dataset** – Post-enrolment updates to name, address, date of birth, gender, and mobile number  
- **Biometric Update Dataset** – Updates to fingerprints, iris, and facial data  

---

## Methodology
- Integrated and cleaned all datasets using a consistent geographic structure  
- Implemented a star schema data model in Power BI  
- Designed the Identity Volatility Score and supporting KPIs such as Update Burden Ratio  
- Performed geographic, temporal, and comparative analysis  

---

## Dashboard Features
- KPI cards showing Identity Volatility Score and Update Burden Ratio  
- Heat-ranked comparison of states by volatility  
- Geographic visualization of volatility distribution  
- Time-series trend analysis  
- Top-10 high-risk regions table  
- Interactive slicers for state-level drill-down  

---

## Tool Used
- **Microsoft Power BI** for data modeling, metric computation, and interactive visualization  

---

## Project Files
- `graphs aadar.pbix` – Interactive Power BI dashboard    
- `README.md` – Project overview and usage instructions
- screenshot of the project: https://github.com/Binusha123/DataAnalysis-Identity-Volatility-Score/blob/main/Screenshot%202026-01-20%20164853.png

---

## How to Use the Dashboard
1. Open `graphs aadar.pbix` using **Power BI Desktop**  
2. Use slicers to filter by state  
3. Explore trends, maps, and rankings to identify high-volatility regions  

---

## Impact and Use Cases
- Helps UIDAI identify regions requiring audit or enrolment quality review  
- Supports data-driven prioritization of resources  
- Reduces operational burden from repeated updates  
- Improves trust and reliability of Aadhaar data  

---

## Conclusion
The Identity Volatility Score demonstrates how a simple, interpretable metric combined with interactive analytics can significantly enhance monitoring of Aadhaar identity stability. The project provides a scalable and actionable framework for proactive data quality management.

