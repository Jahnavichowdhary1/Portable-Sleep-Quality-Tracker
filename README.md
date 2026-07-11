# Portable-Sleep-Quality-Tracker
Developed a portable sleep monitoring system that tracks heart rate, body temperature, and movement. Built an interactive web dashboard to visualize sleep quality scores, sensor trends, sleep history, and personalized sleep insights.
# 😴 Portable Sleep Quality Tracker with Web Interface

## 📖 Project Overview

The Portable Sleep Quality Tracker is an embedded and web-based monitoring system designed to analyse sleep quality using physiological and movement data.

The system monitors parameters such as **heart rate, body temperature, and body movement** during sleep. Sensor values are collected by the embedded system and transmitted for further processing.

An interactive web dashboard was developed to visualise sleep-related information including sleep quality score, heart rate trends, movement activity, and sleep history.

The system analyses the collected parameters and generates a sleep quality score along with personalised sleep recommendations.

---

## 📸 Project Dashboard

<p align="center">
  <img src="images/sleep_dashboard.png" width="90%">
</p>

The dashboard displays the overall sleep quality score, average heart rate, movement activity, and graphical sleep trends.

---

## 🎯 Objectives

- Monitor sleep-related physiological parameters.
- Track heart rate during sleep.
- Detect body movements while sleeping.
- Monitor body temperature.
- Calculate an overall sleep quality score.
- Visualise sleep data through an interactive dashboard.
- Maintain sleep history for analysing sleep patterns.

---

## 🛠️ Technologies Used

### Embedded System

- MSP430 Microcontroller
- UART Communication
- Embedded C
- CCS (Code Composer Studio)

### Web Development

- HTML
- CSS
- JavaScript
- Bootstrap

### Data Visualisation

- Chart.js

### Data Storage

- Browser Local Storage
- CSV Export

---

## 🔄 Project Workflow

```text
Sleep Monitoring Sensors
          │
          ▼
Collect Sensor Data
          │
          ▼
Microcontroller Processing
          │
          ▼
UART Data Transmission
          │
          ▼
Sensor Data API
          │
          ▼
Web Dashboard
          │
          ▼
Sleep Quality Analysis
          │
          ▼
Sleep Score & Recommendations
```

---

## ⚙️ System Parameters

The sleep monitoring system analyses the following parameters:

### ❤️ Heart Rate

Heart rate data is monitored during sleep to identify variations in the user's sleeping condition.

### 🌡️ Body Temperature

Temperature readings are monitored to identify abnormal variations that may affect sleep quality.

### 🏃 Movement Detection

Body movements during sleep are recorded to analyse sleep disturbance and movement activity.

### ⏱️ Sleep Duration

Sleep duration is considered while calculating the overall sleep quality score.

---

## 🧠 Sleep Quality Score

The system calculates a sleep quality score based on:

- Heart rate
- Body temperature
- Number of movements
- Sleep duration

The calculated score is classified into:

- **Good Sleep**
- **Average Sleep**
- **Poor Sleep**

Based on the sleep quality, the system provides sleep improvement recommendations.

---

## 💻 Web Dashboard Features

- Real-time sleep monitoring dashboard
- Sleep quality score visualisation
- Heart rate trend graph
- Movement monitoring
- Weekly sleep duration chart
- Sleep history records
- User profile management
- Dark mode
- CSV data export
- Personalised sleep recommendations

---

## 📊 Sleep History

The dashboard stores previous sleep records containing:

- Date
- Heart rate
- Temperature
- Movement count
- Sleep duration
- Sleep score
- Sleep quality
- Sleep recommendations

Users can export the sleep history as a CSV file for further analysis.

---

## ✨ Key Features

- Portable sleep monitoring system
- Multi-parameter sleep analysis
- Interactive web dashboard
- Graphical sensor data visualisation
- Automatic sleep quality scoring
- Sleep improvement recommendations
- Historical sleep data tracking
- CSV report generation

---

## 🚀 Applications

- Personal Sleep Monitoring
- Sleep Pattern Analysis
- Smart Healthcare Systems
- IoT-based Health Monitoring
- Remote Patient Monitoring

---

## 🔮 Future Improvements

- Integrate real-time IoT cloud storage.
- Develop a mobile application.
- Apply machine learning for sleep stage prediction.
- Add deep sleep and REM sleep classification.
- Implement real-time health alerts.
- Improve sleep score calculation using larger datasets.

---

## 👩‍💻 Author

**Marripalli Jahnavi**
