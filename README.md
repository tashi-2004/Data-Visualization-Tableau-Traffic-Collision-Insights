# Data-Visualization-Tableau-Traffic-Collision-Insights

This repository contains an in-depth data analysis project using Tableau to explore traffic collision data.

## Project Overview
This project analyzes traffic collision data by focusing on injuries, fatalities, contributing factors, and geographic distributions. It uses Tableau’s interactive visualization capabilities to create a series of sheets, dashboards, and an overarching story for easy exploration and understanding of the data.
## Dataset
   - `tashi.csv`: [Download](https://mega.nz/file/bQtlQKDY#bj5GsCbgSy_0HZGGGJYy4yQRrvuZ6VxD5NHHxQctGU4)
## Sheets Overview
Below is a summary of each sheet, detailing the configurations used and the insights provided:

### Sheet 1: Yearly Trend in Injuries and Fatalities
- **Columns**: Year (Crash Date)
- **Rows**: Count Distinct of Injured Persons, Count Distinct of Killed Persons
- **Purpose**: Shows the yearly trend in traffic-related injuries and fatalities, providing insight into overall road safety trends over time.
  <img width="1280" alt="1" src="https://github.com/user-attachments/assets/dd184559-db3f-488e-a17e-446a3ffffb08">

### Sheet 2: Hourly Impact on Cyclist Safety
- **Columns**: Hour (Crash Time)
- **Rows**: Count of Injured Cyclists, Count of Killed Cyclists
- **Purpose**: Analyzes the time of day in relation to cyclist injuries and fatalities, highlighting peak accident times.
  <img width="1280" alt="2" src="https://github.com/user-attachments/assets/6e19006f-cba5-41e0-8c33-d6bad1d8eda5">
### Sheet 3: Yearly Trend for Motorcyclist Injuries and Fatalities
- **Columns**: Year (Crash Date)
- **Rows**: Count of Injured Motorcyclists, Count of Killed Motorcyclists
- **Purpose**: Illustrates trends in motorcyclist injuries and fatalities over the years, providing insights into motorcyclist safety trends.
  <img width="1280" alt="3" src="https://github.com/user-attachments/assets/2fa66281-5227-49db-a460-a72b504a13b8">
### Sheet 4: Pedestrian Safety by Year
- **Columns**: Year (Crash Time)
- **Rows**: Count of Injured Pedestrians, Count of Killed Pedestrians
- **Purpose**: Highlights yearly trends in pedestrian injuries and fatalities, emphasizing pedestrian safety and potential high-risk periods.
  <img width="1280" alt="4" src="https://github.com/user-attachments/assets/1b85304b-2184-44fd-a308-e329175b4283">

### Sheet 5: Impact of Contributing Factors on Pedestrian Safety
- **Columns**: Contributing Factor Vehicle 1
- **Rows**: Average of Injured Pedestrians, Average of Killed Pedestrians
- **Purpose**: Analyzes how various contributing factors impact pedestrian safety, providing insight into potential causes of accidents involving pedestrians.
  <img width="1280" alt="5" src="https://github.com/user-attachments/assets/321ac9ec-641a-4b3e-81be-cc3091fed6dd">
### Sheet 6: Geographic Distribution of Injuries and Fatalities by Zip Code
- **Columns**: Zip Code
- **Rows**: Count Distinct of Injured Persons, Count Distinct of Killed Persons
- **Purpose**: Examines the geographic distribution of injuries and fatalities across different ZIP codes, identifying high-risk areas.
  <img width="1280" alt="6" src="https://github.com/user-attachments/assets/af7be539-6629-4248-b3ef-29d1387690c3">
### Sheet 7: Collision Mapping by Location and Year
- **Columns**: Average Longitude
- **Rows**: Average Latitude
- **Purpose**: Plots collisions on a map by location and year, allowing for a visual analysis of collision patterns across different locations and years.
  <img width="1277" alt="7" src="https://github.com/user-attachments/assets/e9bd9200-6340-4638-984f-097c850389c1">
### Sheet 8: Average Impact on Pedestrians by Borough
- **Columns**: Borough
- **Rows**: Average of Injured Pedestrians, Average of Killed Pedestrians
- **Purpose**: Provides a borough-based analysis of pedestrian injuries and fatalities, highlighting areas with the highest impact on pedestrian safety.
  <img width="1280" alt="8" src="https://github.com/user-attachments/assets/49c4a4c2-8b9d-4b9c-87ae-f6e3eb1689f3">
### Sheet 9: Street-Level Analysis of Injuries and Fatalities
- **Columns**: On Street Name
- **Rows**: Sum of Killed Persons, Sum of Injured Persons
- **Purpose**: Analyzes street-level data for injuries and fatalities, helping to identify specific streets with high accident rates over different years.
  <img width="1280" alt="9" src="https://github.com/user-attachments/assets/ab01fcc6-7643-4833-9040-c75bdb4f46c0">
### Sheet 10: Yearly Total of Injuries and Fatalities by Vehicle Type
- **Columns**: Year (Crash Date)
- **Rows**: Sum of Killed Persons, Sum of Injured Persons
- **Purpose**: Shows the yearly trend of injuries and fatalities by vehicle type, providing insight into vehicle-related accident trends.=
  <img width="1280" alt="10" src="https://github.com/user-attachments/assets/75db39aa-f3c4-4ae4-adf7-c357b6321507">
  
## Dashboards
In addition to the sheets, this Tableau project includes:
- **Dashboards**: Each dashboard consolidates insights from multiple sheets, allowing for interactive exploration of the data.
  
<img width="1263" alt="1" src="https://github.com/user-attachments/assets/c665458a-92b7-4107-834b-e7157866f858">

<img width="1259" alt="2" src="https://github.com/user-attachments/assets/a715b2bb-a055-41de-ab9d-2b51125bb903">

<img width="1262" alt="3" src="https://github.com/user-attachments/assets/4d357766-27ad-455a-bc2f-e2d1fe6f0c2b">

## Key Insights and Recommendations
Based on the analysis, the following insights and recommendations were made:
1. **Trends in Injuries and Fatalities**: Observed fluctuations in injuries and fatalities over the years.
2. **Time of Day Impact**: Certain times of day show higher accident rates.
3. **Vulnerable Road Users**: Cyclists and pedestrians are particularly vulnerable.
4. **Geographical Patterns**: High-risk ZIP code areas identified.
5. **Contributing Factors**: Patterns in contributing factors for injuries and fatalities.

**Recommendations** include awareness campaigns, infrastructure improvements, policy revisions for vehicle safety, data-driven enforcement, and collaboration with local agencies.

## Files
- `Book1.twb`: Contains all sheets, dashboards, and story.
- `Report.pdf`: Summarizes the analysis, insights, and recommendations.

## Contact
- For any questions or suggestions, feel free to contact at [abbasitashfeen7@gmail.com]
