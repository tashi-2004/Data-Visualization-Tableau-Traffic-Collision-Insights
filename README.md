# Data Visualization and Tableau Analysis Project

This repository contains an in-depth data analysis project using Tableau to explore traffic collision data. The project includes 10 distinct sheets, each designed to highlight specific aspects of the dataset, along with dashboards and a story that bring these insights together.

## Project Overview
This project analyzes traffic collision data by focusing on injuries, fatalities, contributing factors, and geographic distributions. It uses Tableau’s interactive visualization capabilities to create a series of sheets, dashboards, and an overarching story for easy exploration and understanding of the data.

## Sheets Overview
Below is a summary of each sheet, detailing the configurations used and the insights provided:

### Sheet 1: Yearly Trend in Injuries and Fatalities
- **Columns**: Year (Crash Date)
- **Rows**: Count Distinct of Injured Persons, Count Distinct of Killed Persons
- **Purpose**: Shows the yearly trend in traffic-related injuries and fatalities, providing insight into overall road safety trends over time.

### Sheet 2: Hourly Impact on Cyclist Safety
- **Columns**: Hour (Crash Time)
- **Rows**: Count of Injured Cyclists, Count of Killed Cyclists
- **Purpose**: Analyzes the time of day in relation to cyclist injuries and fatalities, highlighting peak accident times.

### Sheet 3: Yearly Trend for Motorcyclist Injuries and Fatalities
- **Columns**: Year (Crash Date)
- **Rows**: Count of Injured Motorcyclists, Count of Killed Motorcyclists
- **Purpose**: Illustrates trends in motorcyclist injuries and fatalities over the years, providing insights into motorcyclist safety trends.

### Sheet 4: Pedestrian Safety by Year
- **Columns**: Year (Crash Time)
- **Rows**: Count of Injured Pedestrians, Count of Killed Pedestrians
- **Purpose**: Highlights yearly trends in pedestrian injuries and fatalities, emphasizing pedestrian safety and potential high-risk periods.

### Sheet 5: Impact of Contributing Factors on Pedestrian Safety
- **Columns**: Contributing Factor Vehicle 1
- **Rows**: Average of Injured Pedestrians, Average of Killed Pedestrians
- **Purpose**: Analyzes how various contributing factors impact pedestrian safety, providing insight into potential causes of accidents involving pedestrians.

### Sheet 6: Geographic Distribution of Injuries and Fatalities by Zip Code
- **Columns**: Zip Code
- **Rows**: Count Distinct of Injured Persons, Count Distinct of Killed Persons
- **Purpose**: Examines the geographic distribution of injuries and fatalities across different ZIP codes, identifying high-risk areas.

### Sheet 7: Collision Mapping by Location and Year
- **Columns**: Average Longitude
- **Rows**: Average Latitude
- **Marks**: Color - Collision ID, Detail - Year (Crash Year)
- **Purpose**: Plots collisions on a map by location and year, allowing for a visual analysis of collision patterns across different locations and years.

### Sheet 8: Average Impact on Pedestrians by Borough
- **Columns**: Borough
- **Rows**: Average of Injured Pedestrians, Average of Killed Pedestrians
- **Purpose**: Provides a borough-based analysis of pedestrian injuries and fatalities, highlighting areas with the highest impact on pedestrian safety.

### Sheet 9: Street-Level Analysis of Injuries and Fatalities
- **Columns**: On Street Name
- **Rows**: Sum of Killed Persons, Sum of Injured Persons
- **Marks**: Year of Crash
- **Purpose**: Analyzes street-level data for injuries and fatalities, helping to identify specific streets with high accident rates over different years.

### Sheet 10: Yearly Total of Injuries and Fatalities by Vehicle Type
- **Columns**: Year (Crash Date)
- **Rows**: Sum of Killed Persons, Sum of Injured Persons
- **Marks**: Vehicle Type 1, Vehicle Type 2, Vehicle Type 3, Vehicle Type 4, Vehicle Type 5
- **Purpose**: Shows the yearly trend of injuries and fatalities by vehicle type, providing insight into vehicle-related accident trends.

## Dashboards and Story
In addition to the sheets, this Tableau project includes:
- **3 Dashboards**: Each dashboard consolidates insights from multiple sheets, allowing for interactive exploration of the data.
- **1 Story**: A multi-chapter narrative that provides a cohesive overview of the key findings from the data, focusing on safety trends, contributing factors, and high-risk locations.

## Key Insights and Recommendations
Based on the analysis, the following insights and recommendations were made:
1. **Trends in Injuries and Fatalities**: Observed fluctuations in injuries and fatalities over the years.
2. **Time of Day Impact**: Certain times of day show higher accident rates.
3. **Vulnerable Road Users**: Cyclists and pedestrians are particularly vulnerable.
4. **Geographical Patterns**: High-risk ZIP code areas identified.
5. **Contributing Factors**: Patterns in contributing factors for injuries and fatalities.

**Recommendations** include awareness campaigns, infrastructure improvements, policy revisions for vehicle safety, data-driven enforcement, and collaboration with local agencies.

## Files
- `Tableau_Workbook.twbx`: Contains all sheets, dashboards, and story.
- `Report.pdf`: Summarizes the analysis, insights, and recommendations.

## Workflows
This repository includes a GitHub Actions workflow to validate HTML files on every push or pull request to the main branch, using the W3C HTML Validator for syntax correctness.

---

This project leverages Tableau’s visualization capabilities to facilitate data-driven insights and support decision-making regarding traffic safety.
