# AI-Driven Visitor Monitoring: Visitation Index & Hybrid Anomaly Detection

This repository contains the code and datasets for my Ph.D. research on **automated visitation estimation** and **behavioral anomaly detection** for recreational fishing across Nebraska’s public lakes.  
It integrates anonymized mobility data, fishing permit records, and geospatial lake boundaries into a **hybrid, interpretable machine learning framework** to support fisheries management and conservation.

---

## 📖 Research Overview

### Problem
Traditional visitors monitoring relies on **creel surveys**, **angler reports**, and **permit data**, which are:
- **Slow** – lagging months behind real-world changes.
- **Incomplete** – lacking coverage for all locations/times.
- **Static** – focusing only on total visitor counts without behavioral context.
- **Blind to anomalies** – unable to detect unusual spikes, drops, or irregular use patterns.

### Research Gap
Most existing visitation estimation methods:
- Use **static, volume-based models**.
- Ignore **behavioral trends** like stay duration, frequency, or time-of-day variation.
- Cannot detect **unlabeled anomalies** in visitor patterns.
- Provide **no explainability** for management decisions.

### Research Goals
1. Develop a **Visitation Index** that measures both **frequency** and **intensity** of waterbody use.
2. Implement a **hybrid anomaly detection** framework combining:
   - **Machine learning** 
   - **IQR Logics**
   - **Anomaly Detection Techniques**

