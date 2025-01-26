UK Road Accidend Analysis
======
![Chat Preview](https://imgur.com/LkXxmjt.png)


---


## Overview
This project involved analyzing a dataset of over **300,000 road accidents** to identify patterns, trends, and potential causes of accidents. The objective was to derive actionable insights that could contribute to improving **road safety** and reducing accident frequency.




---

## Problem Statement
The challenge in the project is to discover
1. Analyze changes in casualties and accident counts over time to identify patterns or      improvements.
2. Examine accident counts by severity and potential causes to better understand their      impact and distribution.
3. Create charts and dashboards to highlight key metrics, aiding in identifying             actionable measures for accident prevention.

---
## Dataset
The **road accident dataset** is a real world dataset containing:
- **3lakh sales records**.
- Information about Accident_Index, Date, Accident_Severity, Lat, Lang, etc,.

---
## Project Workflow

1. **Problem Identification**:
   - Figured out the meausres needed to calculate in order to address the problems.
   - Listed out the KPI measures and related charts.

2. **Data Preprocessing**:
   - Loaded the data in Excel and Cleaned raw data.
   - Standardized the colum names, and performed cleaning operation.
   - Got a rough insight about the dataset.
   
3. **Power BI**:

   - Create a Date Table to use Time Intelligent Functions Made (* to 1 relationship b/w two tables)
   - Calculated the measures needed for the project.
   - Visualized all the measures and charts through cards and charts.
   - Developed interactive dashboards 
   
4. **Documentation**:
   - Documented all the DAX Formulas in Word and uploaded it in GitHUB.

Description
Below is the detailed field of each sub-dataset.

## Road accident Analysis - [Link](https://docs.google.com/spreadsheets/d/17ipl5ysT_FOnarho1yWtwdpVX4_62Gg8/edit?usp=sharing&ouid=108123797797737751166&rtpof=true&sd=true)
| Column Name                      | Description                                          | Data Type      |
|----------------------------------|------------------------------------------------------|----------------|
| Accident_Index                   | Unique ID for each accident                          | String         |
| Accident Date                    | Date when the accident occurred                      | Date           |
| Day_of_Week                      | Day of the week when the accident occurred           | String         |
| Junction_Control                 | Type of control at the junction                      | Categorical    |
| Junction_Detail                  | Detailed description of the junction                 | Categorical    |
| Accident_Severity                | Severity level of the accident (e.g., slight, serious, fatal) | Categorical |
| Latitude                         | Latitude coordinate of the accident location         | Decimal        |
| Light_Conditions                 | Lighting conditions at the time of the accident      | Categorical    |
| Local_Authority_(District)       | District of the local authority                      | String         |
| Carriageway_Hazards              | Hazards present on the carriageway                  | Categorical    |
| Longitude                        | Longitude coordinate of the accident location        | Decimal        |
| Number_of_Casualties             | Number of casualties in the accident                 | Integer        |
| Number_of_Vehicles               | Number of vehicles involved in the accident          | Integer        |
| Police_Force                     | Police force jurisdiction where the accident occurred| String         |
| Road_Surface_Conditions          | Surface conditions of the road                      | Categorical    |
| Road_Type                        | Type of road where the accident occurred             | Categorical    |
| Speed_limit                      | Speed limit on the road                              | Integer        |
| Time                             | Time when the accident occurred                      | Time           |
| Urban_or_Rural_Area              | Whether the accident occurred in an urban or rural area | Categorical |
| Weather_Conditions               | Weather conditions at the time of the accident       | Categorical    |
| Vehicle_Type                     | Type of vehicle(s) involved in the accident          | Categorical    |
| Vehicle_Type (groups)            | Grouped categories of vehicle types                  | Categorical    |
| Light_Conditions (groups)        | Grouped categories of lighting conditions            | Categorical    |
| Weather_Conditions (groups)      | Grouped categories of weather conditions             | Categorical    |
| Road_Surface_Conditions (groups) | Grouped categories of road surface conditions        | Categorical    |

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Ruban1504/UK-Road-Accident-Analysis.git
