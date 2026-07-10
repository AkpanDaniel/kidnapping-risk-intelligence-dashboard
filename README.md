# Kidnapping Risk Intelligence Dashboard

A complete analytics project that turns raw incident data into clear, actionable security intelligence. Built with Python, SQL Server, and Power BI.

## What This Project Is About

This isn't a simple chart‑making exercise. I wanted to understand the real patterns behind kidnapping incidents in the Federal Capital Territory.

I took a raw dataset, cleaned it, loaded it into a database, and built a Power BI dashboard that answers specific questions: *where*, *who*, *when*, and *what to do about it*.

The result is a tool that surfaces intelligence, not just numbers.

## The Questions I Wanted to Answer

- Which LGAs are the most dangerous?
- Who is behind most of the kidnappings?
- Is the problem getting worse or better over time?
- Who is being targeted?
- Where should security resources be focused?

## Tools & Tech Stack

- **Python (Pandas)** – data cleaning and initial exploration
- **Power BI** – dashboard design and interactive reporting
- **DAX & Power Query** – measures and data transformation

## Dashboard Pages

### 1. Executive Overview
High‑level KPIs: total incidents, victims, monthly trends, and threat actor breakdown.

### 2. Geographic Risk Analysis
Heatmaps and bar charts showing which LGAs are hotspots, plus monthly trends by location.

### 3. Threat Intelligence & Recommendations
Who the main actors are, which LGA is highest risk, severity analysis, and strategic takeaways.

## Data Model

The star schema is clean and supports all dashboard calculations efficiently.

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/57d40cc3-98d6-42cf-ba3e-b5fdb503750f" />

## Dashboard Preview

<img width="1280" height="704" alt="bi 1" src="https://github.com/user-attachments/assets/5532c8cc-90fc-420c-8273-70b8a2f0b186" />
<img width="1280" height="701" alt="bi 3" src="https://github.com/user-attachments/assets/ce679091-c539-4f22-86dc-f6770dc4eee9" />
<img width="1280" height="701" alt="bi 2" src="https://github.com/user-attachments/assets/4322bf78-f932-4b58-99c4-3910f4a3a9f9" />


## Key Insights

What I actually learned from the data:

- **Concentration**: A few LGAs account for the majority of incidents.
- **Threat actors**: Activity is not evenly spread – certain groups dominate specific areas.
- **Severity vs frequency**: Some LGAs have fewer incidents but more victims per event.
- **Trends**: 2023 was the peak year; numbers have been declining since.


## What’s Next

This dashboard is version 1. I plan to add:

- Live data feeds (or scheduled refresh)
- Incident forecasting
- Geocoding for interactive maps
- Predictive risk scoring for LGAs
- Automated report distribution

## How to Run This Yourself

1. Clone this repository
2. Install Python dependencies (`pandas`, `pyodbc`)
3. Run the cleaning and import scripts
4. Open the Power BI file and refresh the data connection


**Built by [Akpan Daniel](https://github.com/AkpanDaniel)**


---

**Built by [Akpan Daniel](https://github.com/AkpanDaniel)**
