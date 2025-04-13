# Maths_PROJECT_group3

DATA README
----------

Provincial Weather Data Files (2018-2023):
1. AB_combined_weather_data.csv - Alberta
2. BC_combined_weather_data.csv - British Columbia  
3. MB_combined_weather_data.csv - Manitoba
4. NB_combined_weather_data.csv - New Brunswick
5. NL_combined_weather_data.csv - Newfoundland & Labrador
6. NS_combined_weather_data.csv - Nova Scotia
7. NT_combined_weather_data.csv - Northwest Territories
8. NU_combined_weather_data.csv - Nunavut  
9. ON_combined_weather_data.csv - Ontario
10. PE_combined_weather_data.csv - Prince Edward Island
11. QC_combined_weather_data.csv - Quebec
12. SK_combined_weather_data.csv - Saskatchewan
13. YT_combined_weather_data.csv - Yukon

Atmospheric Data Files (2012):
1. wind_speed_2012.csv  
2. wind_direction_2012.csv
3. humidity_2012.csv
4. pressure_2012.csv

Data Specifications:
- Source: All files obtained from Kaggle
- Provincial data: 2018-2023 (Yearly files merged by script 1)
- Atmospheric data: 2012 only (April-June period)

Execution Order:
1. 1_data_merger.py - Combines provincial CSV files
2. 2_data_cleaning.py - Handles missing values and outliers
3. 3_eda.py - Creates exploratory visualizations
4. 4_modeling.py - Runs statistical analysis  
5. 5_forecasting.py - Generates temperature forecasts

Note: 
- Scripts must be run sequentially (1→5)
- Requires Python 3.8+ with pandas, numpy, matplotlib
