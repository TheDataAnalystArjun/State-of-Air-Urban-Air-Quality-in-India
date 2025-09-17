# State of Air: Urban Air Quality in India

An open-source data analysis project exploring air pollution levels across Indian cities using real-time monitoring data.

## 🎯 Goal
Rank Indian cities by air quality and identify high-risk zones for public awareness and policy discussion.

## 📊 Source
Data collected from [Central/State Pollution Control Boards] via open sources (simulated hourly NAQI readings).

> Note: This dataset reflects snapshot conditions on 17-09-2025.

## 🔍 Methodology
- Used `24HrAvgIAQI` as primary metric for stability.
- Aggregated scores at city level using median to reduce outlier bias.
- Ranked cities by median AQI.
- All code written in Python (Pandas, Matplotlib).

## 📈 Findings
- Top polluted: Pithampur (MP), Sri Ganganagar (RJ), Rourkela (OD)
- Cleanest: Tirumala (AP), Ooty (TN), Madikeri (KA)
- Industrial and arid regions show higher pollution trends.

## 🖼️ Visualizations
![Top 10 Polluted Cities](outputs/top_10_polluted_cities.png)

## 🧪 How to Run
```bash
pip install pandas matplotlib seaborn jupyter
jupyter notebook
