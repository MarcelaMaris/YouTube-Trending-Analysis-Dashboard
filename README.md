<p align="center">
  <img src="cover_youtube.png" width="100%" alt="YouTube Trends Dashboard cover">
</p>

## <img src="icons/dashboard.png" width="50">  &nbsp;&nbsp;YouTube Trends Dashboard — Global Video Category Analysis
<br>

![Tableau](https://img.shields.io/badge/Tableau-Public%20Dashboard-0A3756?style=flat&logo=tableau&logoColor=F5F7FA&labelColor=E8AA3A)
![Data](https://img.shields.io/badge/Data-CSV%20Aggregation-0A3756?style=flat&logo=files&logoColor=F5F7FA&labelColor=E8AA3A)
![Visualisation](https://img.shields.io/badge/Visualisation-Area%20%7C%20Pie%20%7C%20Heatmap-0A3756?style=flat&logo=plotly&logoColor=F5F7FA&labelColor=E8AA3A)
![Analytics](https://img.shields.io/badge/Analytics-Trends%20%7C%20Regional%20Insights-0A3756?style=flat&logo=academia&logoColor=F5F7FA&labelColor=E8AA3A)

> This project delivers a **Tableau Public dashboard** to support daily decision-making for  
> video advertising planning managers.
>
> Using an aggregated YouTube trending dataset, the dashboard enables fast answers to:
> - **Which categories were trending last week?**
> - **How do trends differ across regions?**
> - **Which categories are most popular in the United States?**
>
> It mirrors how a **Data Analyst / BI Analyst** would build a self-service reporting product:  
> clear KPI context, interactive filters, and stakeholder-focused visuals.

---

## <img src="icons/objectives.png" width="30">  &nbsp;&nbsp;Objectives

- Build and publish an **interactive Tableau dashboard** for weekly trend monitoring.
- Provide **date and country filters** applied consistently across all views.
- Visualise category trends in both **absolute volume** and **relative share**.
- Enable stakeholders to compare **regional distributions** and identify market-specific patterns.
- Deliver a dashboard layout aligned with a predefined visual prototype and reporting needs.

---

## <img src="icons/features.png" width="30">  &nbsp;&nbsp;Dashboard Structure & Features

### Global controls
- 📅 **Date filter** (applies to all charts)
- 🌍 **Country/region filter** (applies to all charts)

### Visual components
1. **Trend History (Absolute)** — stacked area chart  
   Tracks total trending videos by category across time.

2. **Trending Videos by Country (Share)** — pie chart  
   Shows the percentage distribution of trending videos across selected regions.

3. **Trend History (%)** — 100% stacked area chart  
   Shows each category’s share of total trending volume per day.

4. **Country × Category Table (Heatmap Crosstab)**  
   Highlights category intensity by region using colour-coded values.

---

## <img src="icons/dataset.png" width="30">  &nbsp;&nbsp;Dataset

**File:** `trending_by_time.csv`  
**Source:** Aggregated table from the YouTube database (bootcamp scenario).

**Fields**
- `record_id` — unique row identifier  
- `region` — country or geographic region  
- `trending_date` — date of trending appearance  
- `category_title` — video category  
- `videos_count` — number of trending videos per day, region, and category  

**Refresh cadence:** updated every 24 hours (00:00 UTC).

---

## <img src="icons/dashboard.png" width="30">  &nbsp;&nbsp;Access & Deliverables

🔗 **Live Tableau Public dashboard:**  
https://public.tableau.com/app/profile/marcela.stephanie.pereira.maris1628/viz/YoutubeTreendingDashboard-final/Dashboard1

📊 **Presentation (managerial insights):**  
Open YouTube Trending Dashboard Presentation (OneDrive)

---

## <img src="icons/conclusions.png" width="30">  &nbsp;&nbsp;Key Insights

- **Entertainment** and **Music** are the most recurrent trending categories globally.
- The United States shows strong concentration in high-volume categories, while  
  some regions display greater category diversity.
- **Japan** and **Russia** exhibit broader distribution across categories compared to other markets.
- **Comedy** stands out in certain countries (e.g., France and Japan), but is not dominant worldwide.

---

## <img src="icons/impact.png" width="30">  &nbsp;&nbsp;Business Impact

- Automates recurring reporting, enabling **daily self-service exploration** for ad managers.
- Improves speed and consistency of insight generation across regions and time windows.
- Supports data-driven campaign planning by revealing **market-specific category preferences**.
- Provides a reusable Tableau layout pattern for future trend monitoring dashboards.

---

## <img src="icons/techstack.png" width="30">  &nbsp;&nbsp;Tech Stack

- **BI & Visualisation:** Tableau Public  
- **Data Handling:** CSV-based aggregation, date grouping  
- **Dashboard Design:** stacked area charts, pie chart, crosstab heatmap  
- **Version Control:** Git & GitHub  

---

<p align="center">
  <sub>📊 Designed & developed by <b>Marcela Maris</b> — Data Analytics Portfolio</sub><br>
  <sub><i>BI Dashboards • Trend Analysis • Stakeholder Reporting</i></sub>
</p>

