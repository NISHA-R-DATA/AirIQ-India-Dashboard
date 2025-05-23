![Title_Image](https://github.com/user-attachments/assets/c0c5a7a8-bd9b-4c2b-9947-4be112f13e2d)


## 📘 Project Overview
This project presents a **comprehensive air quality analysis** of **India** for the years **2021** and **2022** using **interactive Tableau dashboards**. Designed to enable **data-informed decision-making**, the dashboard system provides a **macro-to-micro view**—ranging from **national air pollution trends** to **city-level drill-downs**—helping identify **critical pollution zones**, **top pollutants**, and **seasonal variations**. The objective is to empower **environmental policymakers**, **urban planners**, and **researchers** with **real-time visual intelligence** to drive **focused interventions** and monitor **air quality performance** effectively.


*Snapshot of interactive Tableau dashboards developed to analyze India’s air pollution data (2021–2022), featuring national trends, city-level insights, and NAAQS-based pollutant monitoring.*

![Dashboard_1](https://github.com/user-attachments/assets/917131ff-1f14-4c71-9b4b-ea82bebcbbae)


![Dashboard_2](https://github.com/user-attachments/assets/019f477b-9248-4e88-a70f-d1ea4e3220d1)


## 📊 View Live Tableau Dashboard

Click the link below to explore the interactive Tableau dashboard:

👉 [**View Live Dashboard**](https://public.tableau.com/app/profile/nisha.r3849/viz/Air_Pollution_Dashboard/Dashboard1)


---
## 📑 Table of Contents
1. [Business Problem](https://github.com/NISHA-R-DATA/AirIQ-India-Dashboard?tab=readme-ov-file#-business-problem)
2. [Data Source Overview](https://github.com/NISHA-R-DATA/AirIQ-India-Dashboard?tab=readme-ov-file#%EF%B8%8F-data-source-overview)
3. [Tools and Technologies Used](https://github.com/NISHA-R-DATA/AirIQ-India-Dashboard?tab=readme-ov-file#%EF%B8%8F-tools-and-technologies-used)
4. [Analytical Approach](https://github.com/NISHA-R-DATA/AirIQ-India-Dashboard?tab=readme-ov-file#-analytical-approach)
5. [Key Insights](https://github.com/NISHA-R-DATA/AirIQ-India-Dashboard?tab=readme-ov-file#-key-insights)
6. [Strategic Recommendations](https://github.com/NISHA-R-DATA/AirIQ-India-Dashboard?tab=readme-ov-file#-strategic-recommendations)
7. [Conclusion](https://github.com/NISHA-R-DATA/AirIQ-India-Dashboard?tab=readme-ov-file#-conclusion)


---
## 💼 Business Problem
Despite growing **policy attention** and **public awareness**, **India's air quality** has remained **critically poor** in many cities, leading to **chronic health hazards** and **environmental degradation**. There exists a crucial need for:
- A **centralized, intuitive platform** to **monitor**, **analyze**, and **compare air pollution data** across **regions** and **timeframes**.
- **Actionable insights** to identify **pollution sources**, **seasonal spikes**, and **underperforming zones**.
- **Strategic recommendations** tailored to **pollutant types**, **geography**, and **risk levels**.

This project aims to bridge that gap through **dynamic**, **easy-to-interpret Tableau dashboards** grounded in real-world air quality data.

---

## 🗃️ Data Source Overview
- **Dataset Type:** Daily air quality measurements for Indian cities.
- **Time Period:** 1st January 2021 to 31st December 2022.
- **Key Columns:**
  - City, Date, AQI
  - Pollutant Concentrations (μg/m³): CO, NO, NO2, O3, SO2, PM2.5, PM10, NH3
- **Standards Referenced:** National Ambient Air Quality Standards (NAAQS) for both annual and 24-hour limits.
---
## 🛠️ Tools and Technologies Used
- **Data Preparation & Cleaning:** Microsoft Excel
- **Data Visualization:** Tableau
- **Analytics Techniques:** KPI analysis, threshold monitoring, geospatial mapping
- **Performance Indicators:** AQI changes, pollutant concentration thresholds, seasonal variance
---

## 🔍 Analytical Approach

### 1. Data Analyst Workflow
- **Data Cleaning:** Restructured Date field, handled missing pollutant values, normalized AQI metrics.
- **Data Transformation:** Categorized AQI values into bands (Healthy, Moderate, Unhealthy); derived city-wise summaries and month-level aggregations.
- **Exploratory Data Analysis (EDA):** Identified city-level outliers, seasonal cycles, and pollutant frequency distributions.

### 2. Dashboard Development Approach
#### Dashboard 1: Nationwide Air Quality Overview
- **KPI Cards:**
  - Total Records Monitored
  - National Average AQI
  - % Change in AQI
  - Most Polluted City
  - Cleanest City
  - Peak Pollution Month
- **Visuals:**
  - **Map View**: Indian map categorizing cities based on AQI (Green = Good, Orange = Moderate, Red = Poor) with size indicating pollution intensity.
  - **Monthly AQI Trend**: Line chart (2021 vs 2022).
  - **Top 5 Pollutants**: Average concentrations displayed via bar chart.
- **Filters Provided:** Year Slicer
- **Navigation:** Button to city-level drill-down

#### Dashboard 2: City-Level Pollution Drill Down
- **Slicers:** City Selector, Pollutant Selector
- **KPI Cards:**
  - Pollution Overview (City-Specific)
  - Average AQI
  - Peak Pollution Month
  - % Unhealthy AQI Days
- **Visuals:**
  - **Year-over-Year Comparison**: Bar chart for average pollutant concentration with dynamic NAAQS reference line.
  - **Monthly Trend**: Line chart comparing monthly pollutant levels for both years.
  - **Regulatory Exceedance**: % of days per month exceeding 24-hour NAAQS thresholds with visual alerts (Green/Red bars).


---
## 📊 Key Insights

### 1. National Air Quality Overview: Stagnation Despite Efforts
Between 2021 and 2022, India recorded no significant improvement in national air quality, as evidenced by an unchanged average Air Quality Index (AQI) of **3.9** across **18.9K air quality data records**. While this signals a stabilization of overall conditions, it reflects a plateau rather than progress, despite increased policy focus and public engagement.
A marginal AQI decline of **less than 1%** indicates pockets of localized improvement; however, these are insufficient to constitute a national turnaround in air pollution control.



### 2. City-Level Extremes: Persistent Polluters and Clean Air Champions
- **Most Polluted City:**
  **Delhi** retained its status as India’s most polluted city for both years, with an average AQI of **4.8**—categorized as "unhealthy." Key contributors include:
  - Vehicular emissions
  - Industrial discharges
  - Seasonal stubble burning

- **Least Polluted City:**
  **Aizawl** in Mizoram continued to rank as India’s cleanest city. Its naturally clean air can be attributed to:
  - Favorable topography
  - Limited industrial activity
  - High green cover



### 3. Seasonal Trends: Recurring and Predictable Patterns
Air quality followed a **seasonal rhythm** across both years:
- **Winter Peaks (Jan–Feb, Oct–Dec):**
  - Pollution intensified due to temperature inversion, low wind speed, and use of solid fuels for heating.
- **Monsoon Relief (Jun–Aug):**
  - Rainfall significantly reduced airborne pollutants.
- **Pre-Monsoon Transition (Mar–May):**
  - Pollution levels gradually built up with rising temperatures and resumption of urban and agricultural burning activities.



### 4. Key Pollutants: Particulate Matter and Carbon Monoxide 
- **PM2.5 and PM10** levels exceeded **double the permissible limits** of India’s National Ambient Air Quality Standards (NAAQS), indicating critical levels of:
  - Construction dust
  - Unregulated traffic emissions
  - Open biomass burning

- **Carbon Monoxide (CO)** also breached safety limits, especially in urban and peri-urban areas, primarily due to:
  - Vehicular pollution
  - Residential biomass combustion

Conversely, gases like **ozone, sulphur di oxide and nitrogen dioxide** remained largely within safe thresholds, underscoring the dominant role of fine particulate pollution.



### 5. High-Risk Zones: Year-Round Health Hazards
Cities such as **Delhi, Amritsar, Jorapokhar, and Patna** experienced "unhealthy" air for **over 95% of the year**, showing:
- Consistent PM2.5 and PM10 exceedances
- Frequent CO spikes—particularly in **October and November**, driven by:
  - Diwali-related emissions
  - Crop residue burning

Though some CO spikes were short-lived, their frequency contributes to chronic exposure risk.


### 6. Moderately Polluted Cities: At Risk but Recoverable
Cities including **Ahmedabad, Mumbai, Hyderabad, Bhopal, Guwahati, and Visakhapatnam** maintained AQI levels between **3.2 and 4.1**, bordering high-risk thresholds.
- **Pollution Timing:** Peaks observed in **January–March** and **November–December**
- **Primary Pollutants:** PM2.5 and PM10
- **Encouraging Sign:** Cities like **Shillong** showed year-over-year improvement, hinting at the potential success of localized interventions such as:
  - Better traffic management
  - Construction dust regulation



### 7. Clean Air Cities: Sustainable Urban Planning Pays Off
Cities with AQI consistently below 3.3 included:
- **Thiruvananthapuram**
- **Bengaluru**
- **Kochi**
- **Coimbatore**
- **Ernakulam**
- **Aizawl**

**Common success factors:**
- Abundant green infrastructure
- Limited industrial footprint
- Effective urban planning
- Geography favorable to pollution dispersion

These cities serve as **models of sustainable air quality management**.



### 8. Key Takeaways and Actionable Insights
- **Particulate matter (PM2.5 and PM10)** is the most critical pollutant nationwide.
- **Carbon monoxide** levels indicate severe vehicular and residential combustion challenges.
- **Seasonal weather patterns** exacerbate pollution in winter and mitigate it during monsoons.
- While nationwide air quality remained static, **city-level improvement** in the region like **Shillong** highlight the potential of targeted, data-driven interventions.


---
## 🧭 Strategic Recommendations

### 1. National-Level Strategies:
- Launch an **Air Quality Performance Index (AQPI)** with reward-penalty mechanisms.
- Real-time NAAQS compliance systems.
- National PM2.5 Mitigation Mission: electric vehicles, cleaner fuels, dust regulation.

### 2. Seasonal and Regional Plans:
- **Winter:** Ban on biomass burning, electric heating in North India.
- **Diwali:** Regulate firecrackers, promote eco-friendly alternatives.
- **Monsoon:** Clean-air drives, tree planting campaigns.

### 3. City-Level Interventions:
- Classify cities as Red/Amber/Green and enforce tailored action plans.
- Boost green infrastructure, walkable urban design, and strict construction norms.

### 4. Pollutant-Specific Actions:
- **PM2.5/PM10:** Traffic regulation, emission controls.
- **CO:** Upgrade emission standards; clean cooking in slums.

### 5. Technology and Data:
- AI-driven predictive models for pollution surges.
- Centralized open data platform combining sensors, satellites, and public reporting.

### 6. Community Engagement:
- **Citizen science:** Distribute low-cost AQ monitors.
- **Education:** Integrate air quality awareness in school curriculum.

---

## 🏁 Conclusion
This project demonstrates the power of **data visualization** and **analytics** in tackling **pressing environmental issues**. By converting **raw pollution data** into **actionable intelligence**, it facilitates **smarter decision-making** at both **policy** and **citizen levels**. The **dual-dashboard design** ensures both **macro** and **micro perspectives** are addressed—making this solution ideal for **government bodies**, **urban developers**, **NGOs**, and **researchers** focused on **sustainable air quality improvement**.
