# 🏏 IPL Data Analytics Pipeline (2008 - 2025)

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

## 📌 Project Overview
This project delivers a comprehensive end-to-end analysis of the Indian Premier League (IPL) spanning 17 years. It transforms a raw dataset of over **278,000 rows** into an interactive business intelligence dashboard. 

The project demonstrates a professional data workflow: **Extraction → Cleaning (Python) → Modeling → Visualization (Power BI).**

---

## 🛠️ The Technical Workflow

### 1. Data Engineering & Cleaning (Python)
The raw data contained inconsistencies due to team rebranding and missing match results. I developed a Python script (`IPL_Cleaning.ipynb`) to:
* **Team Standardization:** Mapped legacy names (e.g., *Kings XI Punjab*) to current names (*Punjab Kings*) to ensure historical data continuity.
* **Data Integrity:** Handled `DtypeWarnings` by enforcing schema types and removed "No Result" matches to ensure accurate win/loss ratios.
* **Feature Engineering:** Programmatically calculated **Strike Rates**, **Total Wickets**, and **Aggregate Runs** for top-tier analysis.

### 2. Data Modeling & BI (Power BI)
The cleaned data was imported into Power BI to build a robust analytical engine:
* **Star Schema Modeling:** Created relationships between match, batter, and bowler dimensions.
* **AI-Powered Insights:** Integrated a **Linguistic Schema** allowing users to ask natural language questions (e.g., *"Who had the highest strike rate in 2024?"*).
* **Interactive UI:** Designed a multi-page report with drill-through capabilities to view specific team and player performances.

---

## 📊 Key Insights Captured
* **Player Milestones:** Identification of the Top 10 run-scorers and wicket-takers across 17 seasons.
* **Team Evolution:** Visualizing how team performance shifted after rebranding and squad changes.
* **Venue Analysis:** Impact of home-ground advantage on winning percentages.

---
## 🚀 How to Use
1.  **Python:** Run the notebook in the `Notebooks/` folder to see the data transformation logic.
2.  **Power BI:** Open the `.pbix` file in Power BI Desktop to interact with the dashboard.
  ---
  **Developed by Ashish Kumar Rajak**
  **Data Analyst | Python | Power BI |*
