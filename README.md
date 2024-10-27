# Data Visualization and Tableau Project

This repository contains an interactive data visualization project focused on analyzing traffic collision data. Using Tableau, I have created an in-depth story to present key insights from the dataset, including multiple dashboards and sheets. Below is an overview of the dataset, columns, and the visualizations included in the Tableau workbook.

## Dataset Overview
The dataset used in this project can be accessed here: [Traffic Collision Data](https://mega.nz/file/bQtlQKDY#bj5GsCbgSy_0HZGGGJYy4yQRrvuZ6VxD5NHHxQctGU4).

### Columns
The dataset includes the following columns:
- **CRASH_DATE**: Date of the crash (object)
- **CRASH_TIME**: Time of the crash (object)
- **BOROUGH**: Borough where the crash occurred (object)
- **ZIP_CODE**: ZIP code of the crash location (object)
- **LATITUDE**: Latitude of the crash location (float64)
- **LONGITUDE**: Longitude of the crash location (float64)
- **LOCATION**: Combined latitude and longitude (object)
- **ON_STREET_NAME**: Street where the crash occurred (object)
- **CROSS_STREET_NAME**: Cross street near the crash (object)
- **OFF_STREET_NAME**: Off-street location of the crash (object)
- **INJURED_PERSONS**: Number of people injured (float64)
- **KILLED_PERSONS**: Number of people killed (float64)
- **INJURED_PEDESTRIANS**: Number of pedestrians injured (float64)
- **KILLED_PEDESTRIANS**: Number of pedestrians killed (float64)
- **INJURED_CYCLISTS**: Number of cyclists injured (float64)
- **KILLED_CYCLISTS**: Number of cyclists killed (float64)
- **INJURED_MOTORISTS**: Number of motorists injured (float64)
- **KILLED_MOTORISTS**: Number of motorists killed (float64)
- **CONTRIBUTING_FACTOR_VEHICLE_1-5**: Contributing factors of up to five vehicles involved (object)
- **COLLISION_ID**: Unique identifier for each collision (float64)
- **VEHICLE_TYPE_1-5**: Types of up to five vehicles involved (object)

## Tableau Visualization Details
To analyze and visualize this data, I have created the following in Tableau:

- **10 Sheets**: Each sheet presents specific aspects of the dataset, such as location, time, injuries, fatalities, and contributing factors.
- **3 Dashboards**: These dashboards bring together multiple sheets, enabling interactive exploration of the data by location, contributing factors, and time.
- **1 Story**: The story is a multi-chapter presentation that highlights key findings and insights from the data. Each chapter addresses a unique aspect of the dataset, such as patterns in crash timing, location hotspots, and factors contributing to crashes.

## Key Insights and Recommendations
Based on the analysis in Tableau, the following insights and recommendations were identified:

### Key Insights
1. **Trends in Injuries and Fatalities**: There are variations over the years in the number of injuries and fatalities, reflecting changes in road safety and traffic regulation effectiveness.
2. **Time of Day Impact**: Certain hours show notably higher injury and fatality rates, especially affecting cyclists and pedestrians, indicating peak accident times.
3. **Vulnerable Road Users**: Cyclists and pedestrians account for a significant portion of injuries and fatalities, underscoring their vulnerability on the road.
4. **Contributing Factors**: Patterns in contributing factors reveal associations with more severe incidents, particularly involving certain vehicle types.
5. **Geographical Patterns**: Injury and fatality counts differ across zip codes, suggesting some areas face higher risks, potentially due to traffic density or road conditions.

### Recommendations
1. **Targeted Awareness Campaigns**: Launch public safety campaigns focused on times and locations with high accident rates, targeting all road users with safety practices.
2. **Infrastructure Improvements**: Improve safety infrastructure in high-risk areas, such as adding signage, bike lanes, and pedestrian crossings to protect vulnerable users.
3. **Policy Revisions for Vehicle Safety**: Revise safety standards for vehicle types that contribute to high injury and fatality rates, possibly restricting certain models in urban zones.
4. **Data-Driven Enforcement**: Leverage contributing factor data to better enforce regulations during peak accident times, targeting behaviors like speeding and distracted driving.
5. **Collaboration with Local Agencies**: Partner with transportation and safety agencies for tailored initiatives that address specific safety needs in each borough or zip code.

## Files
- `Tableau_Workbook.twbx`: The Tableau workbook containing all sheets, dashboards, and story.
- `Report.pdf`: A brief report summarizing the analysis, key insights, and recommendations.

---

This project leverages Tableau's interactivity and data visualization capabilities to uncover meaningful insights and facilitate data-driven decision-making.
