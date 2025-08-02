🌦️ Real-Time Weather Dashboard | Power BI

An interactive and visually rich Power BI dashboard designed to display real-time and forecasted weather conditions for six major cities in Pakistan. Initially connected to a weather API for dynamic updates, the dashboard now uses static data (dated 18 July 2025) due to the API’s free plan expiration—common for student and personal projects.

📍 Cities Covered: Karachi, Lahore, Islamabad, Quetta, Peshawar, Gilgit

📊 Project Overview

This dashboard tracks and visualizes:

🌡️ Current temperature & conditions

☀️ 7-day forecast trends

🌅 Sunrise and sunset timings

🌬️ Wind, humidity, pressure, and visibility

💧 Chance of rain (daily)

🔆 UV Index & precipitation levels

🟠 Air Quality Index (AQI) with pollutant breakdown

It was originally designed to auto-refresh daily using API-based connections, and now presents archived weather data for demo/reference purposes.

📁 Project Structure

Weather_Report_PowerBI/
   │ 
   ├── Assets/  
   │   ├── Lahore_2025-07-18.PNG  
   │   └── Gilgit_2025-07-18.PNG  
   │
   ├── Data/ 
   │   ├── Current_Data.xlsx         # Current weather conditions 
   │   ├── Forecast_Day.xlsx         # 7-day forecast data
   │   ├── Forecast_Hrs.xlsx         # Hourly forecast (not visualized)
   │   └── Location.xlsx             # City metadata (IDs, coords)
   │ 
   ├── Weather_Dashboard.pbix        # Power BI report file 
   └── README.md                     # Project documentation

🧠 Features & Design Highlights

● Dynamic API integration (historically enabled real-time updates).

● Dark-themed modern UI for readability and clarity.

● Custom AQI classification with color-coded indicators (Good, Moderate, Unhealthy).

● Forecast trend lines using Power BI line charts.

● Rain probability bars with horizontal bar chart format.

● Modular card visuals for temperature, wind, humidity, and visibility.

● Built-in refresh scheduling when API was live.

📷 Screenshots

Lahore (18 July 2025)	

Gilgit (18 July 2025)

🔗 Data Sources

Initially powered by OpenWeatherMap API using free-tier access. Current version uses snapshot Excel files exported on 2025-07-18 due to key expiration.

🔧 How to Use

● Clone/download the repository.

● Open Weather_Dashboard.pbix in Power BI Desktop.

● Review and analyze weather insights by selecting different cities.

● To re-enable real-time updates:

● Replace the Excel data sources with live API queries.

● Use Power Query (M) to connect and transform incoming JSON.

📌 Notes

The current version is static for demo and portfolio use.

Forecast_Hrs.xlsx is included for completeness but not used in visuals.

This project can be extended for:

Mobile optimization

Multi-country coverage

Historical weather comparison

👨‍💻 Author

Abrar Shakeel

Data Science & Visualization Enthusiast


📄 License
This project is for educational and demonstration purposes only. API use subject to terms from the respective providers.
