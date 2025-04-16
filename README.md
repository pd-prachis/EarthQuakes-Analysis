#Earthquakes-Analysis-Dashboard

📊 Dashboard Link: https://app.powerbi.com/groups/me/reports/38844816-c5a8-4e29-989f-258a7fc38345/4a85a568b3cd93580072?experience=power-bi
📄 PDF Link: https://github.com/pd-prachis/EarthQuakes-Analysis/blob/main/Earthquakes%20%20Analysis.pdf

📌 Problem Statement
This dashboard has been developed to analyze and monitor global earthquake data. The primary objective is to understand the frequency, intensity, depth, and location-based trends in earthquake occurrences over time.

By using this dashboard, geoscientists, emergency planners, and policymakers can:

Identify patterns in earthquake magnitude and depth.

Monitor historical earthquake frequency across decades.

Determine seasonal trends in seismic activity.

Assess high-risk regions based on historical quake counts.

Investigate the relationship between magnitude and depth to improve risk prediction models.

🛠️ Steps Followed
Step 1: Loaded the earthquake dataset (CSV format) into Power BI Desktop.

Step 2: Opened Power Query Editor and enabled:

Column Quality

Column Distribution

Column Profile
→ Ensured column profiling was applied to the entire dataset.

Step 3: Cleaned the dataset:

Replaced nulls, especially in Magnitude Type (magType) and Depth columns.

Ensured correct data types for numeric and date columns.

Step 4: Created custom DAX measures and calculated columns to:

Aggregate total earthquake counts.

Group by year, month, magnitude, depth, and magType.

Step 5: Created visuals including:

Bar charts, histograms, scatter plots, and map visuals.

Included interactive filters for Year and Magnitude Type.

Step 6: Applied a clean, dark theme and aligned visuals with consistent formatting.

Step 7: Published the report to Power BI Service for sharing and stakeholder access.

📈 Key Performance Indicators
Total Earthquakes Analyzed: 8,313
Spanning over 100+ years of data, this dashboard reflects comprehensive seismic activity records.

📊 Dashboard Insights
🔢 Total Earthquakes by Year
Earthquake counts increase steadily from early 1900s to 2000s, indicating better data collection or increased seismic activity.

Years around 2000–2020 exhibit notably higher earthquake counts compared to earlier decades.

📆 Earthquakes by Month
Earthquake occurrences are evenly distributed across the months.

Slightly higher counts in January (94) and February (95).

No extreme seasonal trend observed, suggesting seismic activity is largely random across months.

📏 Earthquakes by Magnitude
Majority of earthquakes fall within magnitude 6–7 range, followed by magnitude 8.

Magnitude 6: 1,182 occurrences

Magnitude 7: 926 occurrences

Magnitude 8: 469 occurrences

Magnitude 9: 365 occurrences

Magnitude 10: Very rare

🌎 Earthquakes by Location
Map visuals highlight frequently affected regions (not visible in PDF but implied through spatial plotting).

Useful for regional disaster preparedness and monitoring.

🌡️ Earthquake Depth Histogram
Most earthquakes occur at shallow depths.

Depth 0–200 km: 6.8K earthquakes

Depths beyond 200 km are rare.

Indicates crustal earthquakes are most common and generally more destructive.

📉 Depth vs. Magnitude Relationship
A scatter plot reveals no strong correlation between magnitude and depth:

High-magnitude quakes can occur both in shallow and deep regions.

Depths beyond 400 km rarely exceed magnitude 7.

Useful for understanding how depth contributes to surface damage potential.

🧾 Earthquakes by Magnitude Type
Magnitude types include: mb, ms, mj, Mt, Mw, mwb, and blanks.

Mw (Moment Magnitude) is the most common and reliable modern standard.

💡 Key Takeaways
Magnitude 6–7 earthquakes dominate the global earthquake landscape.

Shallow earthquakes (0–200 km) are significantly more frequent and potentially more damaging.

No clear seasonal pattern, meaning earthquakes can occur in any month.

Data reflects an increasing trend over years, possibly due to better detection systems or more frequent seismic activity.

Magnitude type standardization is necessary as some entries are missing magType values.

Visuals like Depth vs Magnitude can aid researchers in understanding energy release patterns during seismic activity.

💼 Technologies Used
Power BI Desktop

Power Query Editor

DAX (Data Analysis Expressions)

Custom Measures and Visuals

Power BI Service for Web Deployment

✅ Outcome
This dashboard transforms complex seismic data into easily digestible, interactive visuals for geoscientists, civil engineers, emergency responders, and government bodies. It supports risk mitigation, resource allocation, and public awareness initiatives through data-driven insights into global earthquake activity.

📬 To access the interactive dashboard or collaborate on geospatial analysis, feel free to connect.

