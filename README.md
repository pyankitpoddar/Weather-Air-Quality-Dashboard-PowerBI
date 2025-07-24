# Weather & Air Quality Dashboard (Power BI)

This Power BI project offers a visually rich and interactive dashboard displaying real-time weather and air quality data for Noida and comparable cities. It’s designed for anyone needing actionable weather, pollution, and meteorological insights at a glance.

https://app.powerbi.com/view?r=eyJrIjoiNTllYWJmMDAtNjMwNC00ZjQ3LWI5YzgtNWU5MDA2YTJlOGNkIiwidCI6ImFjZjRkYzIxLTAxYmUtNDlmNS1iN2UxLWFlMzYwOWJiZWJjNSJ9

---

## 📍 Overview

- **Location:** Primary—Noida. Quick stats for Bengaluru, Chennai, Kolkata, Mumbai, New Delhi.
- **Core Capabilities:** Live weather status, 7-day temperature forecast, AQI breakdown, precipitation chance, sunrise/sunset, and other atmospheric measures.

---

## 🎯 Features

- **Weather Card:** Instant display of city temperature, sky status (e.g., mist), and basic metrics.
- **Forecast Chart:** Visual 7-day temperature trendline.
- **Sunrise/Sunset Module:** Clearly listed daily timings.
- **Air Quality Index:** Prominent AQI score with “hazard” flagging; breakdown by PM10, PM2.5, SO<sub>2</sub>, CO, O<sub>3</sub>, NO<sub>2</sub>.
- **Rain Probability:** Bar visualization of daily rain likelihood.
- **Environmental Stats:** Humidity, wind speed, visibility, pressure, UV index, and precipitation.

---

## 📊 Visual Components

- **KPI Tiles:** Quick-glance stats (temp, wind, humidity, UV, etc.).
- **Line Chart:** 7-day temperature projection.
- **Horizontal Bar Chart:** Daily rain probability.
- **Donut/Gauge:** AQI severity visualization.
- **Pollutant Table:** All pollutant readings side by side.

---

## 💡 How to Use (Power BI)

1. **Open the Dashboard:**
    - Launch the `.pbix` file with Power BI Desktop.
2. **Data Refresh:**
    - To update, click “Refresh” in the ribbon (for metadata/API pull).
    - For live data, configure “Scheduled refresh” if publishing to Power BI Service.
3. **Interact with Visuals:**
    - Hover over charts or bars for precise stats.
    - Switch city quick-views as needed.
4. **Modify or Extend:**
    - Drag in additional cities or data sources.
    - Adjust visuals, colors, or add alert banners for high AQI or severe weather.

---

## 🔄 Enabling Data Refresh

- **Manual Refresh:**
    - Click the “Refresh” icon in Power BI Desktop.
- **Scheduled Refresh (Power BI Service):**
    - Go to your dataset > “Scheduled refresh”, set your parameters (frequency, time).
    - Ensure API keys and data gateway (if needed) are set up in dataset settings.

---

## 🌐 Data Sources

- **Weather:** WeatherAPI, or comparable JSON/CSV feeds
- **Air Quality:** WeatherAPI, or comparable JSON/CSV feeds

---

## 📝 Requirements

- Microsoft Power BI Desktop (latest)
- Internet access for API refresh
- API keys for weather/AQI providers (configured via Data Source settings)
