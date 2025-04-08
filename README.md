# Real-Time Earthquake Data Analysis 🌍

This project fetches and analyzes real-time earthquake data using the **USGS Earthquake API**. It retrieves data on recent seismic activity worldwide, processes the information using Python, and provides insights like the strongest earthquakes, affected regions, and magnitudes.

---

## 📡 Data Source

- **USGS Earthquake Hazards Program**  
  API Endpoint: [https://earthquake.usgs.gov/](https://earthquake.usgs.gov/)

---

## 📊 Features

- Fetches real-time earthquake data using the USGS GeoJSON feed.
- Analyzes data for:
  - Largest magnitude earthquakes
  - Most affected locations
  - Earthquake frequency by magnitude range
- Saves data to a CSV file.
- Easy to customize (e.g., filter by country, date, magnitude).

---

## 🛠️ Tools Used

- Python
- Pandas
- Requests
- Matplotlib / Seaborn (for visualization)

---

## 🧠 Insights (Sample)

- Max magnitude in last 24 hours: 6.2 near Japan
- 50+ earthquakes above magnitude 4.5 in the past 7 days
- Most active regions: Indonesia, California, South America

---

## 📁 Files

| File Name               | Description                                |
|------------------------|--------------------------------------------|
| `earthquake_analysis.py` | Python script to fetch and analyze data     |
| `recent_earthquakes.csv` | Output file containing latest earthquake data |
| `README.md`             | Project documentation                      |

---

## 🗺️ Map[Uploading earthquakes_map.html…]()

![Earthquake_on_map](https://github.com/user-attachments/assets/13d7e705-4573-4301-b854-2202a6f9435f)

## 🔧 How to Run

1. Install dependencies:
   ```bash
   pip install pandas requests
