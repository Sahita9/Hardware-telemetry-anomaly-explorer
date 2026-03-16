*Hardware Telemetry Anomaly Explorer*

An interactive multi-axis time-series dashboard for visualizing and detecting anomalies in 
simulated hardware telemetry data — including thermal zones, voltage rails, SoC power 
draw, and PMU performance counters.
Built to demonstrate hardware-aware signal analysis, feature engineering, and interactive 
visualization skills relevant to silicon validation and hardware performance engineering.
Features
• Multi-axis time-series visualization — 4 synchronized subplots with shared x-axis 
and unified hover
• Anomaly detection — Z-score thresholding for voltage droops and power 
anomalies; rate-of-change detection for thermal spikes
• Feature engineering — Rate-of-change signals, rolling averages, z-score 
normalization
• Interactive controls — Range slider for time window selection, annotated anomaly 
markers, dark theme
• Simulated hardware signals:
o Thermal zone temperature (°C) with injected spikes
o Voltage rail (V) with injected droops
o SoC power draw (W) with rolling average overlay
o PMU performance counter with injected drops
Tech Stack
• Python 3.x
• Plotly — interactive visualization
• Pandas — data manipulation
• NumPy — signal simulation
• SciPy — statistical analysis (z-score)
Getting Started
1. Clone the repo
git clone: https://github.com/Sahita9/Hardware-telemetry-anomaly-explorer.git
cd hardware-telemetry-anomaly-explorer
2. Install dependencies
pip install -r requirements.txt
3. Run the dashboard
python telemetry_explorer.py
The dashboard will open in your browser automatically.
Sample Output
The dashboard displays:
• Thermal signal with rate-of-change overlay and anomaly markers
• Voltage rail with highlighted droop windows
• Power draw with rolling average trend line
• PMU performance counter
Console output includes an anomaly summary and descriptive statistics for all signals.
Skills Demonstrated
• High-frequency time-series analysis and feature engineering
• Statistical anomaly detection (z-score, rate-of-change thresholding)
• Interactive multi-axis visualization with Plotly
• Hardware telemetry signal interpretation (thermal, voltage, power, performance)
• Clean, reproducible Python scripting for large-scale data workflows
