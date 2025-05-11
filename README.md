# Daily_Ridership
Exploratory data analysis of MTA transit data, comparing ridership trends, pandemic recovery, and external influences.
# 🚇 MTA Daily Ridership Analysis Project

_A data science project focused on analyzing and forecasting public transportation ridership trends._

---

## 👥 Our Team

- Sarah Emad  
- Tasneem Mohsen  
- Alyaa Ibrahim  
- Fatma Hassan  
- Momen Haithem  
- Galal Eldeen Mohamed  

---

## 🎯 Project Overview

This project aims to analyze MTA daily ridership data to identify trends in subway, bus, and commuter rail usage. The goal is to:

- Assess ridership recovery post-pandemic  
- Understand peak travel times  
- Explore factors affecting transit usage  

**Data Source**: MTA Open Data (aggregated from MetroCard/OMNY tap-ins and automated counters)  
- **Data File**: [📂 MTA Daily Ridership Data](https://github.com/sarahh-emadd/Daily_Ridership/blob/main/data/MTA_Daily_Ridership.csv)
-  **Data Dictionary**: [📂 MTA Daily Ridership Data](https://github.com/sarahh-emadd/Daily_Ridership/blob/main/data/MTA_data_dictionary.csv)


---

## 📌 Objectives

- Identify peak ridership hours for different modes  
- Analyze subway, bus, and rail ridership over time  
- Compare current ridership to pre-pandemic levels  
- Evaluate external factors (COVID-19, weather, economy)  
- Provide actionable insights for planning & policy  

---

## 🔍 Project Scope

- Data collection and cleaning from MTA records  
- Exploratory Data Analysis (EDA) and visualizations  
- Trend identification and forecasting using ML  
- Develop interactive dashboards for insights  

---

## 📊 Data Description

**Dataset Name**: MTA Daily Ridership  
**Source**: Metropolitan Transportation Authority (MTA)  
**Date Range**: Starting March 1, 2020  
**Granularity**: Daily  

**Fields**:
- Date  
- Estimated Ridership for:
  - Subways  
  - Buses  
  - LIRR (Long Island Rail Road)  
  - Metro-North Railroad  
  - Access-A-Ride (paratransit)  
  - Bridges and Tunnels  
  - Staten Island Railway  
- % of Pre-Pandemic Ridership  

---

## 🏗️ Data Modeling & System Design

**Technologies Used**:
- Python: `pandas`, `matplotlib`, `seaborn`, `plotly`  
- SQL  
- Power BI & Tableau  

**Machine Learning**:
- Time Series Forecasting using Prophet, ARIMA, or XGBoost  

**Visualization**:
- Power BI & Tableau dashboards  
- Python-based visualizations  

---

## 👥 Stakeholder Analysis

| Stakeholder            | Role                     | Interest                                               |
|------------------------|--------------------------|--------------------------------------------------------|
| MTA Operations Team    | Service planners         | Optimize scheduling & reduce costs                    |
| City Government        | Policy makers            | Ensure effective public fund usage                    |
| Commuters              | End users                | Reliable, safe transit options                        |
| Data Analysts          | Insight developers       | Provide actionable recommendations                    |
| Budget Office          | Finance managers         | Align funding with actual demand                      |

---

## 📈 Key Performance Indicators (KPIs)

| Metric                                | Success Indicator                                  |
|---------------------------------------|----------------------------------------------------|
| Peak Ridership Hours Identified       | Determine busiest travel periods                   |
| Subway vs. Bus vs. Rail Trends        | Compare usage across different transit types       |
| Pre vs. Post-Pandemic Recovery        | Track recovery rates post-COVID                    |
| Forecast Accuracy                     | Accuracy of future ridership predictions           |
| Interactive Data Visualization        | Clear and actionable dashboard visuals             |

---

## Insights from our Analysis

| Insights                                |
|---------------------------------------|
|**1- Post-COVID Recovery**: Some transportation modes (e.g., subway or bus) likely recovered faster than others like LIRR or Metro-North. Normalized plots probably show Subway rebounding sooner due to higher dependencein urban areas.  |
| **2- Weekend vs Weekday Trends**: Ridership patterns may differ significantly between weekdays and weekends. Recommendations might include adjusting service frequency or staffing based on observed usage. Weekend ridership is lower across all modes. Transit demand is highest on weekdays, suggesting potential for off-peak scheduling savings.|
|**3- Seasonal or Temporal Trends**: Monthly or yearly breakdowns could reveal seasonal drops (e.g., holidays) or long-term recovery trends |
|**4- Total Ridership Trends**: Identification of overall rising or falling ridership trends post-2020. Important for capacity planning and infrastructure investments. |
|**5- Forecasting**: If ARIMA was applied to total_ridership, the model may project future demand, helping in planning service levels.       |
|**6- Mode Recovery Trends**: From normalized ridership trends: Subways and buses likely showed faster recovery post-COVID. Commuter rails (LIRR, Metro-North) lagged—likely due to ongoing hybrid/remote work reducing daily suburban commutes.|
|**7- Total Ridership Rebound**: Total ridership shows a gradual upward trend, which is a strong signal of recovery. Fluctuations may align with seasonal patterns or COVID variant surges. |

---

## Recommendations You Could Derive

| Recommendations                                |
|---------------------------------------|
|**1- Resource Allocation**:Increase service where recovery is strongest (e.g., subways on weekdays), reduce frequency for underused services.|
|**2- Targeted Marketing**: Promote LIRR or Metro-North through pricing or service incentives to stimulate slower-recovering ridership.|
|**3- Policy Interventions**: Consider flexible schedules or hybrid work policies to distribute peak demand more evenly. |
|**4- Forecast-Driven Planning**: Identification of overall rising or falling ridership trends post-2020. Important for capacity planning and infrastructure investments. |



---

##  Conclusion

This project provided a comprehensive analysis of MTA daily ridership trends from the onset of the COVID-19 pandemic through the recovery phase. By examining patterns across various transit modes—including subways, buses, LIRR, Metro-North, and paratransit services—we identified how different parts of the transportation system were impacted and how they are rebounding over time.

## Key Takeaways

- Subways and buses experienced the steepest initial drop but also demonstrated the strongest recovery, especially on weekdays.

- Commuter rail services like LIRR and Metro-North have shown slower ridership recovery, indicating potential overcapacity or changes in commuter behavior (e.g., remote work).

- Ridership varies significantly by day of the week and season, with weekdays and fall months seeing higher usage.

- Forecasting models (e.g., ARIMA) suggest that full ridership recovery is ongoing but uneven across modes.

- Cost considerations reveal that buses and subways remain the most cost-effective transit options, whereas commuter rail and paratransit services are more expensive per rider.

## Recommendations

- Prioritize service adjustments and investments in subway and bus systems, where rider recovery is strongest.

- Reevaluate the frequency and scale of commuter rail services to align with changing demand patterns.

- Implement targeted outreach and marketing for underutilized services.

- Use forecasting outputs to guide staffing, budgeting, and maintenance planning.

- Integrate these findings into a dashboard for ongoing monitoring, decision-making, and stakeholder communication.






---


## Links
- **Our presentation**: [📂 MTA Daily Ridership Presentation](https://www.canva.com/design/DAGmSeguEIo/SNOXkPJCTElD2xpWjoUMwQ/edit)
- **PowerBI Dashboard**: [📂 MTA Daily Ridership Data](https://github.com/sarahh-emadd/Daily_Ridership/blob/main/outputs/PowerBIdashboard.pdf)
- **Project Report**: [📂 MTA Daily Ridership Data](https://github.com/sarahh-emadd/Daily_Ridership/blob/main/outputs/Project_Report.pdf)
- **Python NoteBook**: [📂 MTA Daily Ridership Data](https://github.com/sarahh-emadd/Daily_Ridership/blob/main/notebooks/project-mta-depi.ipynb)
- **Machine Learning NoteBook**: [📂 MTA Daily Ridership Data](https://github.com/sarahh-emadd/Daily_Ridership/blob/main/notebooks/proj-depi-mta-daily.ipynb)
- **SQL**: [📂 MTA Daily Ridership Data](https://github.com/sarahh-emadd/Daily_Ridership/blob/main/notebooks/SQLite.sql)


