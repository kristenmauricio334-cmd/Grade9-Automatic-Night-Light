# Grade 9-Automatic-Night-Light

# Project Description
The Automatic Night Light Monitoring is a simple monitoring system designed to determine whether an area is dark or bright using an analog light sensor reading.

The project uses a Streamlit dashboard to display the sensor readings and monitor changes in light levels. Users can adjust the sensor reading through a slider, and the dashboard automatically displays a warning when the reading is above the set threshold.

When the sensor reading is above 500, the system displays "DARK: LED ON". Otherwise, it displays "BRIGHT: LED OFF".

# Objectives
- To monitor the amount of light using sensor readings.
- To identify whether the surroundings are dark or bright.
- To demonstrate how an automatic night light system works.
- To display sensor readings using a Streamlit dashboard.

# Technologies Used
- Python – Main programming language.
- Streamlit – Used to create the monitoring dashboard.
- Pandas – Used to organize and display sensor data.
- Arduino – Used for the hardware implementation of the project.

# Project Files
- sketch.ino – Modified Arduino program
- app.py – Streamlit monitoring dashboard
- requirements.txt – Required Python libraries
- README.md – Project description and documentation

# How It Works
1. The user adjusts the analog sensor reading using the slider.
2. The system checks the reading against the threshold of 500.
3. If the reading is above 500, it displays "DARK: LED ON".
4. If the reading is 500 or below, it displays "BRIGHT: LED OFF".
5. The dashboard displays the sensor reading and a line chart of sample data.

# Expected Outcome
The expected outcome is a working monitoring dashboard that demonstrates how light levels can be detected and classified to control an automatic night light.

# Conclusion
The Automatic Night Light Monitoring project demonstrates how Python, Streamlit, and sensor technology can be used to create a simple automatic lighting monitoring system. It helps users understand how sensor readings can be used to determine when a light should turn on or off.
