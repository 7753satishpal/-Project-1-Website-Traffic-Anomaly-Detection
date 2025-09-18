# 🔧 IoT Sensor Data – Anomaly Detection  

## 📌 Problem Statement  
IoT devices continuously generate large amounts of data such as temperature, pressure, or humidity readings. Malfunctioning sensors or unexpected events can cause **anomalous readings**, which may lead to system failures if undetected.  

The goal of this project is to **detect anomalies in sensor data** using statistical and machine learning methods.  

---

## 🛠️ Tools & Libraries  
- Python (Pandas, NumPy)  
- Matplotlib, Seaborn (Visualization)  
- Scikit-learn (Isolation Forest)  
- Statsmodels / Rolling Window (Time series analysis)  

---

## 🔧 Approach  
1. **Dataset Creation**: Simulated IoT sensor readings (temperature values) with injected anomalies (spikes & drops).  
2. **Exploratory Data Analysis (EDA)**: Visualized trends, seasonality, and irregularities.  
3. **Anomaly Detection Methods**:  
   - Rolling mean & Z-Score  
   - Isolation Forest (ML-based anomaly detection)  
4. **Visualization**: Highlighted anomalies on the time series plot.  

---

## 📊 Key Insights  
- Detected **sharp spikes** in temperature that may indicate faulty sensor readings.  
- Identified **sudden drops** which could represent hardware malfunction or data transmission errors.  
- Isolation Forest flagged subtle anomalies that traditional Z-score missed.  

---

## 📂 Files in Repository  
- `iot_anomaly.ipynb` → Jupyter notebook with code, analysis & plots  
- `data/sensor.csv` → Sample IoT sensor dataset  
- `images/anomaly_plot.png` → Visualization with anomalies marked  

---

## 🚀 Results & Impact  
- Demonstrated how anomaly detection can be applied to **IoT monitoring systems**.  
- Early detection helps prevent **downtime, safety hazards, and costly repairs**.  
- Techniques can be extended to other IoT applications (smart homes, manufacturing, healthcare).  

---

⭐ *This project shows practical anomaly detection in time series IoT data, combining statistical and ML-based methods.*  
