📊 Excel | Power Query | Data Analysis

# Hospital Operations Analytics Dashboard (Excel)

## Overview

This project analyzes hospital patient flow, waiting times, and revenue using Microsoft Excel.
The goal is to demonstrate how operational insights can be extracted from healthcare data using tools commonly used by data analysts.

The dashboard was built using:

* Power Query for data cleaning and transformation
* Pivot Tables for analysis
* Excel charts for visualization
* An interactive dashboard layout with slicers

---

## Dataset

The dataset simulates hospital visit records across multiple quarters.

Key fields include:

* Visit ID
* Arrival Time
* Consultation Start Time
* Consultation End Time
* Department
* Visit Type (Walk-in / Scheduled)
* Outcome  
* Insurance
* Follow up
* Revenue

Data from four quarters (Apr 2025 – Jan 2026) were combined using Power Query.

---

## Key Analysis Questions

The project investigates:

1. Which departments experience the longest patient waiting times?
2. How do waiting times differ between walk-ins and scheduled appointments?
3. Which departments generate the most revenue?
4. What other insights can be discovered?

---
## Workflow



---

## Dashboard

![Dashboard Overview](images/dashboard_overview.png)

The dashboard displays:

* Average waiting time by department
* Walk-in vs appointment waiting times
* Revenue contribution by department
* Monthly patient volume and revenue trends
* Further detailed waiting times by department

Interactive slicers allow filtering by:

* Department
* Quarter

---

## Key Insights

**1. Emergency department shows the longest waiting times**

Emergency visits had the highest average waiting time, indicating potential operational bottlenecks.
Up to 92% of patients had a waiting time of over 30 minutes. Further review should be conducted by the hospital to determine if infrastructure, manpower or both is responsible for this result.

**2. Walk-in patients wait significantly longer**

Walk-ins experienced substantially longer waiting times compared to scheduled appointments.
An awareness campaign via flyers and direct messaging at the end of the hospital pipeline can be directed to users who are found to walk in more for non-admission purposes rather than setting up an appointment.

**3. Cardiology generates high revenue per patient**

Although patient volume was lower, cardiology services generated strong revenue, earning around $600 per patient.

---

## Tools Used

* Microsoft Excel
* Power Query
* Pivot Tables
* Data Visualization

---

## Project Purpose

This project demonstrates how Excel can be used to perform exploratory data analysis and build operational dashboards for healthcare settings.

It was created as part of a data analytics portfolio.

---

## Author

Harish Dubey
