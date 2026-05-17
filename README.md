# 🛢️ Predictive Maintenance & Anomaly Detection — Industrial Sensor Data

> End-to-end anomaly detection pipeline on multi-channel industrial sensor data, modelled on production ML work delivered at Ferrari S.p.A (Maranello, Italy).

## 📌 Project Overview

Equipment failure in industrial operations causes millions in downtime, safety hazards, and environmental damage. This project builds a production-style anomaly detection system on oil well sensor data — the same domain and methodology applied during real predictive maintenance work on Ferrari's engine assembly line.

Three detection methods are implemented, compared, and evaluated:

- Z-Score — Statistical — Point anomalies, sudden spikes/drops
- Rolling Statistics — Adaptive threshold — Slowly shifting baselines  
- Isolation Forest — ML Multivariate — Complex multi-sensor anomalies

## 🔧 Tech Stack

- Python — NumPy, Pandas, Matplotlib, Seaborn
- Machine Learning — Scikit-learn, Isolation Forest, StandardScaler
- Time Series — Rolling statistics, STL decomposition
- Evaluation — Precision, Recall, F1, Confusion Matrix

## 🔗 Related Experience

This project is modelled on production ML work delivered at Ferrari S.p.A (Maranello, Italy) where anomaly detection pipelines were built on real engine test bench sensor data and deployed via Flask REST APIs to support the engine assembly line.

## 👩‍💻 Author

Uzma Latif — Data Scientist | ML Engineer | AI Researcher  
Email: uzmalatif777@gmail.com  
LinkedIn: https://www.linkedin.com/in/uzma-latif-4b2604130  
GitHub: https://github.com/UzmaLatif
