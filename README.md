# 🚶 Walk vs 🏃 Run Activity Classification

## 📌 Project Overview
This project focuses on classifying human physical activity (**Walk vs Run**) using sensor data from accelerometer and gyroscope signals.

It uses Machine Learning models to analyze motion patterns and accurately predict whether a person is walking or running.

---

## 📊 Dataset Information
- 📁 File: `walkrun.csv`
- 📌 Total Records: 88,588
- ⚖️ Balanced Dataset:
  - Walk: 44,223 (49.9%)
  - Run: 44,365 (50.1%)
- 📅 Duration: June 30 – July 9, 2017
- 👤 Subject: Viktor
- 📡 Sensors Used:
  - Acceleration (X, Y, Z)
  - Gyroscope (X, Y, Z)

---

## 🚀 Features
- 📊 Interactive Dashboard (HTML + Chart.js)
- 📈 Data Visualization:
  - Activity Distribution
  - Sensor Analysis
  - Signal Patterns
- 🤖 Machine Learning Models:
  - Random Forest ✅ (Best)
  - Gradient Boosting
  - Logistic Regression
- 📉 Model Comparison & Metrics
- 🎯 Feature Importance Analysis
- 🔮 Live Activity Predictor (Simulation UI)
- ⚡ FastAPI Deployment Ready

---

## 🧠 Model Performance
| Model                 | Accuracy |
|----------------------|---------|
| Random Forest        | 99.18% ✅ |
| Gradient Boosting    | 98.40% |
| Logistic Regression  | 86.39% |

---

## 🔍 Key Insights
- 📐 **Acceleration Y** is the most important feature (~48%)
- ⚖️ Dataset is perfectly balanced (no bias issue)
- 🌀 Gyroscope improves classification accuracy
- 🎯 Random Forest achieves near-perfect performance
- 📍 Wrist position has minimal impact

---

## 🛠️ Tech Stack
- Python 🐍
- Pandas & NumPy
- Scikit-learn
- Joblib
- FastAPI
- HTML, CSS, JavaScript
- Chart.js
