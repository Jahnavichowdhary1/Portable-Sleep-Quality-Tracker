# 😴 Portable Sleep Quality Tracker with Web Interface

## 📖 Project Overview

The Portable Sleep Quality Tracker is an embedded and web-based monitoring system designed to analyse sleep quality using physiological and movement data.

The system monitors parameters such as **heart rate, body temperature, and body movement** during sleep. Sensor values are collected by the embedded system and transmitted for further processing.

An interactive web dashboard was developed to visualise sleep-related information including sleep quality score, heart rate trends, movement activity, and sleep history.

The system analyses the collected parameters and generates a sleep quality score along with personalised sleep recommendations.

---

## 📸 Web Dashboard

<p align="center">
  <img src="images/sleep_dashboard.png" width="90%">
</p>

<p align="center">
  <b>Portable Sleep Quality Tracker Dashboard</b>
</p>

The web dashboard displays the **sleep quality score, heart rate, movement activity, and sleep-related graphical data** in an easy-to-understand interface.

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
- Code Composer Studio (CCS)

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

## ⚙️ Parameters Monitored

### ❤️ Heart Rate

Heart rate data is monitored during sleep to analyse variations in the user's sleeping condition.

### 🌡️ Body Temperature

Temperature readings are monitored to identify variations that may affect sleep quality.

### 🏃 Movement Detection

Body movements during sleep are recorded to analyse sleep disturbances and movement activity.

### ⏱️ Sleep Duration

Sleep duration is considered while calculating the overall sleep quality score.

---

## 🧠 Sleep Quality Score

The system calculates a sleep quality score based on:

- Heart rate
- Body temperature
- Movement activity
- Sleep duration

The calculated score is classified as:

- **Good Sleep**
- **Average Sleep**
- **Poor Sleep**

Based on the sleep quality, the dashboard provides sleep improvement recommendations.

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
- Remote Health Monitoring

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
