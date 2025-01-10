## Title
Machine Downtime Dashboard

## Dashboard
![Screenshot 2025-01-06 110704](https://github.com/user-attachments/assets/d00dab03-0564-4af0-8f99-a5f65f6e7740)


## Project Objective
The primary goal of this project is to analyze and monitor machine downtime events to identify patterns, reduce operational disruptions, and optimize overall equipment efficiency in manufacturing processes. This includes understanding downtime causes, monitoring performance metrics, and identifying areas for improvement.

## Dataset Used
Key Fields:
Machine ID
Downtime events
Spindle speed (RPM)
Vibration metrics
Hydraulic pressure (bar)
Coolant temperature
Assembly line numbers
Time period (Date range from 24-11-2021 to 03-07-2022)

## KPIs
Total Downtime Events: 1,265
Average Spindle Speed: 20.23K RPM
Average Vibration in Machines: 32.88K
Highest Hydraulic Pressure: 252.51K bar
Uptime vs. Downtime Ratio:
Uptime: 101.20
Downtime: 0.00 (ratio as shown)
Monthly Downtime Trends by Assembly Line: Breakdown provided in graph.

## Process
Data Collection: Collect machine performance metrics from shop floors across assembly lines.
Data Cleaning & Preparation: Filtered and structured data by machine ID, downtime type, assembly line, and time periods.
Dashboard Development: Created interactive visuals, including pie charts, bar charts, and line graphs, to present trends and insights.
Analysis: Monitored downtime events, uptime ratios, and the performance of machines.

## Project Insights
### Machine Downtime Distribution:

"Makino-L2-Unit1-2015" experienced the highest number of downtimes (874 events, 34.96%).
"Makino-L1-Unit1-2013" and "Makino-L3-Unit1-2015" had slightly lower but comparable downtime counts (808 and 818 events, respectively).

### Downtime by Type:

Machine failures (454 for Makino-L1, 415 for Makino-L3) are slightly more frequent than machine downtime (420 for Makino-L1, 403 for Makino-L3).

### Monthly Trends:
Downtime peaked in March and April 2022 across all shop floors (Shopfloor-L1, L2, and L3).
A significant decline in downtime events was observed from May to July 2022.

### Spindle Speed Trends:
Spindle speed performance has improved steadily from 2021 to 2022.

### Key Metrics Impact:
Hydraulic pressure and coolant temperature are directly correlated with downtime events, as highlighted in scatter plots.

## Conclusion

This dashboard provides a clear visualization of machine performance and downtime patterns. Key takeaways include:

Makino-L2-Unit1-2015 requires priority focus due to its high downtime events.
March and April represent critical months with the highest downtime; the causes should be further investigated.
Continuous improvements in spindle speed performance are encouraging, potentially contributing to reduced downtimes post-May 2022.
Focus on minimizing machine failures and optimizing hydraulic pressure/coolant systems to further reduce downtime events.

## Recommendations:
Schedule preventive maintenance for Makino-L2 machines to address frequent downtimes.
Conduct root cause analysis for peak downtime periods (March–April) and implement corrective actions.
Use vibration and hydraulic pressure metrics for predictive maintenance alerts.
