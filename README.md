# Tableau_Citi_Bike

## Short Project Overview

This project analyzes Citi Bike usage data from February to April 2024 for the New York metropolitan area, focusing on identifying trends, anomalies, and opportunities for improvement.

The **['Tableau_Citi_Bikes'](https://github.com/LegallyNotBlonde/Tableau_Citi_Bike/blob/main/Tableau_Citi_Bikes.twbx)** includes the Tableau workbook, and you can explore the interactive dashboards on my **[Tableau Public Book](https://public.tableau.com/app/profile/sabrina.linden/viz/Book4_17254336170670/MainStory?publish=yes).**
___

## Key Findings (Tableau)

1. **Long Duration Rides:** 
<p> Classic bikes exhibit a higher number of long-duration rides (over 20 hours) compared to electric bikes, especially among casual users. These rides are not typically associated with long distances, suggesting possible user errors (e.g., forgetting to check out) or technical issues.
This graph ![Long Ride Anomalies](https://github.com/LegallyNotBlonde/Tableau_Citi_Bike/blob/main/Images/Long%20Ride%20Anomalies.png) compares ride durations with distances, indicating that the longest rides covered only a few miles.

* **Recommendation:** 
* Investigate potential system issues or user behavior. 
* Implement alerts or reminders to prevent extended rides, improving bike availability and reducing unexpected charges.

2. **Peak vs. Long Rides:** 
<p> Peak commuting hours show high usage but not longer ride durations. Longer rides are observed during midday, early mornings, and weekends, indicating leisure or exercise use.
This graph ![Bike Demand By Weekday](https://github.com/LegallyNotBlonde/Tableau_Citi_Bike/blob/main/Images/Bike%20deman%20By%20Weekday.png) shows that the longest rides occur on weekends, while the highest number of rides typically happens on Fridays and Mondays.
* Expand station coverage near parks and popular leisure areas.
* Promote biking for both commuting and leisure during non-peak hours through targeted campaigns.


3. **Identifying the Month with the Lowest Demand:** 
<p> In the New York metropolitan area, February experiences the lowest ride demand, making it the ideal time to schedule maintenance and minimize disruptions.
This graph ![Bike demand By Month](https://github.com/LegallyNotBlonde/Tableau_Citi_Bike/blob/main/Images/Bike%20Demand%20By%20Month.png) illustrates these findings.

4. **Most Popular Stations:** 
<p> New Jersey emerges as the most popular starting and ending point for rides, with limited trips between New York and New Jersey.

* **Recommendation:**  
* Optimize bike distribution by increasing availability in New Jersey during peak hours.
* Promote cross-city trips and analyze time-of-day patterns to balance supply and demand effectively.
* Ensure sufficient bike availability at high-demand end stations to reduce shortages and congestion.
___

* **Conclusion:** 

<p> Implementing the recommendations listed above will provide Citi Bike with key benefits, including:

* **Increased Bike Availability:** Optimized distribution and reduced long-duration rides enhance bike access during peak times.
* **Operational Efficiency:** February maintenance minimizes disruptions during high-demand months.
* **Higher Revenue:** Expanded stations and cross-city trip promotions attract more riders.
* **Cost Savings:** Alerts for extended rides cut operational expenses and disputes.
* **Balanced Demand:** Better distribution reduces shortages and improves efficiency.

<p> These strategies address current challenges and position Citi Bike for growth and improved user satisfaction.
___

## Methodology
* **Data Cleaning:** Pandas Libraries
* **Visualization:** Tableau
___

## Resources
[Citi bike](https://citibikenyc.com/system-data)