**Poultry Farm Environmental Data Analysis**

Project Overview

This project analyses environmental monitoring data collected from three
sensor nodes within a commercial poultry farm:

- Node 1 – Baby Chick Section
- Node 2 – Main East Zone
- Node 3 – Main West Zone

The project uses Python to clean, validate, process and analyse environmental
sensor data to identify trends, anomalies and differences in environmental
conditions across the farm.

The analysis focuses on environmental factors such as temperature, humidity,
ammonia (NH3), particulate matter (PM2.5 and PM10), noise, light, H2S,
NO2 and TVOC.

**Objectives**
- Clean and validate environmental sensor data.
- Combine data collected from three sensor locations.
- Compare environmental conditions across different farm zones.
- Identify trends and unusual environmental readings.
- Perform time-based analysis of environmental conditions.
- Examine relationships between environmental variables.
- Assess potential environmental risks.
- Prepare the processed data for Power BI dashboard development.

Environmental variables analysed include:
- Temperature
- Humidity
- NH3 (Ammonia)
- H2S
- NO2
- PM2.5
- PM10
- TVOC
- Noise
- Light

**Data Cleaning and Preprocessing**

The preprocessing process included:

- Checking for missing values.
- Checking for duplicate records.
- Identifying hidden missing values.
- Converting timestamps into datetime format.
- Checking timestamp continuity.
- Validating environmental measurement ranges.
- Combining datasets from the three sensor nodes.
- Creating hour, day and month variables for time-based analysis.
- Assigning sensor readings to their corresponding farm zones.

  **Key Insights**

The analysis identified several important patterns:

- Environmental conditions varied across the three monitoring locations.
- Particulate pollution levels changed according to location and time.
- PM2.5 and PM10 showed a strong positive relationship.
- Temperature displayed noticeable changes throughout the day.
- Some environmental measurements contained unusual spikes that required
  further investigation.
- Differences between farm zones demonstrated the importance of
  location-specific environmental monitoring.

**Visualisations**

The project uses several visualisations to communicate analytical findings,
including:

- Environmental comparison by sensor node
- PM2.5 trends over time
- Temperature trends
- NH3 trends
- PM2.5 and PM10 risk distributions
- Correlation heatmap

**Technologies Used**

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Visual Studio Code
- Power BI

 **Recommendations**

Based on the analysis:

- Environmental conditions should continue to be monitored across individual
  farm zones.
- Ventilation should be reviewed in locations experiencing elevated
  particulate matter.
- Regular cleaning and waste management can help control ammonia accumulation.
- Temperature should be carefully monitored in the baby chick section.
- Automated monitoring could help identify unusual environmental conditions
  earlier.

** Conclusion**
  
This project demonstrates how environmental sensor data can be transformed
into meaningful information using Python.

The analysis identified differences in environmental conditions across
different areas and time periods within the poultry farm. The project
demonstrates the value of data-driven environmental monitoring for supporting
better operational decision-making.
