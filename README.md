# HealthConnect Clinic Appointment Analysis

## Project Overview
This project analyses HealthConnect Clinic appointment data to understand appointment attendance and no-show patterns and identify factors that may be associated with missed appointments.

The analysis will be developed across multiple weeks, beginning with data understanding and quality assessment and progressing to exploratory analysis, KPIs, visualisations, insights, and recommendations.

## Week 4: Project Kickoff and Data Understanding

### Dataset
- 5,000 appointment records
- 18 variables

### Initial Data Quality Findings
- No duplicate records identified
- Data types were consistent with the Data Dictionary
- No inconsistent or invalid values identified during the initial review
- 90 missing values (2%) in `distance_to_clinic_km`
- 60 missing values (1%) in `waiting_time_minutes`

## Week 4 Project Files
- [Project Summary](./HealthConnect_Project_Summary.pdf)
- [Initial Analysis Report](./HealthConnect_Initial_Analysis.pdf)
- [Data Quality View](./Data_Quality_View.pdf)

## Key Insights (Week 5)
- Attendance is close to a coin flip. Only 46.28% of scheduled appointments were attended, with a 48.46% no-show rate — indicating a systemic attendance problem rather than an occasional issue.
- Past behavior is the strongest predictor of future no-shows. The no-show rate rises sharply with prior no-show history — from 43.51% with 0 previous no-shows to 100% for patients with 5 previous no-shows — showing repeat no-show behavior compounds over time.
- Reminders alone are not solving the problem. Reminder Coverage stands at 72.68%, yet no-show rates remain high regardless of whether a reminder was sent (47.63% no-show among reminded patients vs. 51.39% among those not reminded) — suggesting reminders help marginally but aren't a fix on their own.
- No-shows are not day-specific. No-show rates stay fairly consistent across all weekdays (46-51%), meaning the problem isn't tied to particular scheduling days and requires a broader intervention.
- No-show rates fluctuate seasonally but stay persistently high. Monthly no-show rates range from 42.17% (November) to 53.85% (December), showing some seasonal variation but never dropping to a healthy baseline at any point in the year.
- Booking lead time may be a contributing factor. With an average booking lead time of 30 days, longer gaps between booking and appointment date could be giving patients more opportunity to forget or deprioritize their visit — worth deeper investigation in Week 6.
## Analysis Files 
- [Dashboard] (./HealthConnect.pdf)
## Tools Used
- Power BI
- Power Query
- Microsoft Word

## Project Status
Week 4 completed: Initial data understanding and quality assessment.

Further analysis, visualisations, insights, and recommendations will be added in the coming weeks.

## Author
**Kudirat Abiola Shonibare**  
Data Analytics
