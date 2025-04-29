# Formula Junior Series Performance Analyzer
*A predictive model to identify future Formula 1 talent using Formula 2 and Formula 3 data*
**By Andry Rakotonjanabelo**

## Project Overview
This machine learning project analyzes Formula 2 and Formula 3 performance data to predict which junior drivers are most likely to succeed in Formula 1. The model evaluates race results, qualifying performance, lap times, and career progression patterns.

## Key Features
- **Data Ingestion**:  Reading race data from CSV files and structured HTML tables.
- **Exploratory Data Analysis (EDA)**:  Analyzing F2 and F3 datasets to identify key performance indicators and trends.
- **Data Cleaning and Preprocessing**:  Handling missing values, inconsistencies, and data type conversions for model training.

## Data Sources
| Source | Description | Access Method |
|--------|-------------|---------------|
| F2 Race Results (2018-2019) |  Race results for F2 seasons, including laps, times, gaps, and driver information. | CSV Files |
| F3 Teams & Drivers (2019) | List of teams, drivers, chassis, and engine details for the F3 season. | CSV Files |
| F3 Driver Standings (2023) | Standings for the 2023 F3 season, including points, wins, and other statistics. | CSV Files |

## Data Columns of Interest
### F2 Race Results
- LAPS
- TIME
- GAP
- KPH
- BEST (Best Lap Time)
- PILOT NAME
- TEAM

### F3 Teams and Drivers
- Team
- Chassis
- Engine
- Driver

### F3 Driver Standings
- Driver
- Entrant
- RS (Races Started)
- W (Wins)
- PD (Podiums)
- P (Points)
