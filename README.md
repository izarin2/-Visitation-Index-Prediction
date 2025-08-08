# AI-Driven Fisheries Monitoring: Visitation Index & Hybrid Anomaly Detection

This repository contains the code and datasets for my Ph.D. research on **automated visitation estimation** and **behavioral anomaly detection** for recreational fishing across Nebraska’s public lakes.  
It integrates anonymized mobility data, fishing permit records, and geospatial lake boundaries into a **hybrid, interpretable machine learning framework** to support fisheries management and conservation.

---

## 📖 Research Overview

### Problem
Traditional fisheries monitoring relies on **creel surveys**, **angler reports**, and **permit data**, which are:
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
   - **Machine learning** (Isolation Forest, Local Outlier Factor)
   - **Rule-based logic**
   - **Statistical z-score verification**
3. Integrate heterogeneous datasets for **scalable, explainable, and real-time monitoring**.

---

## 🛠 Methodology

1. **Data Cleaning & Integration**
   - Align geospatial lake boundaries with mobility points.
   - Standardize date formats and variable names.
   - Remove duplicates and fix inconsistencies.

2. **Feature Extraction & Selection**
   - Key attributes: visit counts, duration, day type, permit type, distance traveled.

3. **Modeling**
   - **Visit Volume Forecasting** (Random Forest, XGBoost, RNNs)
   - **Visit Duration Prediction**
   - **Hybrid Anomaly Detection**:
     - Isolation Forest for pattern-based anomalies.
     - Rule-based detection for expert-defined thresholds.
     - Z-score for statistical outliers.

4. **Visitation Index Calculation**
   - Normalize and combine volume, duration, and anomaly scores.
   - Output as a **single interpretable metric**.

---

## 📂 Repository Structure
