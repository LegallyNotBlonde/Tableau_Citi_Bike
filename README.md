# Tableau_Citi_Bike

## Project Overview

This project analyzes Citi Bike usage data from February to April 2024 for the New York metropolitan area, focusing on identifying trends, anomalies, and opportunities for improvement. 
Expanding the analysis period to include a full year of data is recommended to ensure the accuracy and consistency of findings across different seasons.

The **Tableau_Citi_Bikes'** includes the Tableau workbook, and you can explore the interactive dashboards on my **[Tableau Public Book](https://public.tableau.com/app/profile/sabrina.linden/viz/Book4_17254336170670/MainStory?publish=yes).**
___

## Key Findings (Tableau)
The graphs effectively illustrate some of the key findings, highlighting patterns and insights in the data.

1. **Long Duration Rides:** 
<p> Classic bikes exhibit a higher number of long-duration rides (over 20 hours) compared to electric bikes, especially among casual users. These rides are not typically associated with long distances, suggesting possible user errors (e.g., forgetting to check out) or technical issues.
<p>The dashboard below compares ride durations with distances, indicating that the longest rides covered only a few miles.

![Long Ride Anomalies](https://github.com/LegallyNotBlonde/Tableau_Citi_Bike/blob/main/Images/Long%20Ride%20Anomalies.png) 

* **Recommendation:** 
* Investigate potential system issues or user behavior. 
* Implement alerts or reminders to prevent extended rides, improving bike availability and reducing unexpected charges.


2. **Peak vs. Long Rides:** 
<p> Peak commuting hours show high usage but not longer ride durations. Longer rides are observed during midday, early mornings, and weekends, indicating leisure or exercise use.

<p> These bar charts show that the longest rides occur on weekends, while the highest number of rides typically happens on Fridays and Mondays.

![Bike Demand By Weekday](https://github.com/LegallyNotBlonde/Tableau_Citi_Bike/blob/main/Images/Bike%20deman%20By%20Weekday.png) 

* **Recommendation:** 
* Expand station coverage near parks and popular leisure areas.
* Promote biking for both commuting and leisure during non-peak hours through targeted campaigns.


3. **Identifying the Month with the Lowest Demand:** 
<p> In the New York metropolitan area, February experiences the lowest ride demand, making it the ideal time to schedule maintenance and minimize disruptions.

The graphs below illustrate these findings:

![Bike demand By Month](https://github.com/LegallyNotBlonde/Tableau_Citi_Bike/blob/main/Images/Bike%20Demand%20By%20Month.png) 

4. **Most Popular Stations:** 
<p> New Jersey emerges as the most popular starting and ending point for rides, with limited trips between New York and New Jersey.

* **Recommendation:**  
* Optimize bike distribution by increasing availability in New Jersey during peak hours.
* Promote cross-city trips and analyze time-of-day patterns to balance supply and demand effectively.
* Ensure sufficient bike availability at high-demand end stations to reduce shortages and congestion.
___

## How This Analysis Benefits the Company and Its Riders/Clients

<p> Implementing the recommendations listed above will provide Citi Bike with key benefits, including:

* **Increased Bike Availability:** Optimized distribution and reduced long-duration rides enhance bike access during peak times.
* **Operational Efficiency:** February maintenance minimizes disruptions during high-demand months.
* **Higher Revenue:** Expanded stations and cross-city trip promotions attract more riders.
* **Cost Savings:** Alerts for extended rides cut operational expenses and disputes.
* **Balanced Demand:** Better distribution reduces shortages and improves efficiency.

<p> These strategies address current challenges and position Citi Bike for growth and improved user satisfaction.

___

## Methodology
* **Data Collection:** Downloaded annual trip data as ZIP files
* **Data Cleaning:** Processed and cleaned datasets using Pandas to handle missing values and ensure consistency
* **Analysis:** Performed exploratory data analysis (EDA) to identify trends and anomalies
* **Visualization:** Designed interactive dashboards in Tableau to present insights effectively
___

## Resources
[Citi bike](https://citibikenyc.com/system-data)