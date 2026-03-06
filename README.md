# <h1 align='center'> 🚚 DELHIVERY - Business Case Study 🚚 </h1>
<h1 align='center'> Feature Engineering </h1>
<h2 align='right'>Analysed by : <font color='red'><b> RITESH</b></font></h2>

---

## 📝 Case Report

- You can access the complete Python notebook here  
➡️ [Python Notebook](Ritesh_Delhivery_Feature_Engineering.ipynb)

- You can access the complete case study report here  
➡️ [Project Report](Ritesh_Delhivery_Feature_Engineering.pdf)

---

## Introduction

**Delhivery**, founded in 2011, is one of India’s largest logistics and supply chain companies.  
It provides services such as express parcel transportation, warehousing, and last-mile delivery across the country.

With the help of advanced technology and data-driven operations, Delhivery handles millions of shipments and aims to optimize logistics efficiency.

This case study focuses on analyzing logistics data and performing **feature engineering** to improve delivery predictions and operational insights.

---

## 🔹 Why this Case Study?

This case study helps to understand:

• Data preprocessing and cleaning  
• Handling missing values and outliers  
• Feature engineering for predictive modeling  
• Logistics route analysis  
• Identifying operational inefficiencies  

These insights help improve delivery efficiency and logistics planning.

---

## 🔹 Business Objective

Delhivery wants to understand the data coming from its logistics pipelines in order to:

- Clean and preprocess delivery data
- Extract useful features from raw logistics data
- Compare predicted vs actual delivery metrics
- Improve forecasting models and operational efficiency

---

## 📊 Dataset Features

| Feature | Description |
|-------|-------------|
| data | Indicates whether the data is training or testing |
| trip_creation_time | Timestamp of trip creation |
| route_schedule_uuid | Unique route schedule ID |
| route_type | Transportation type |
| trip_uuid | Unique trip identifier |
| source_center | Origin warehouse |
| source_name | Source warehouse name |
| destination_center | Destination warehouse |
| destination_name | Destination warehouse name |
| od_start_time | Trip start time |
| od_end_time | Trip end time |
| start_scan_to_end_scan | Delivery time between scans |
| actual_distance_to_destination | Actual delivery distance |
| actual_time | Actual delivery time |
| osrm_time | Predicted delivery time |
| osrm_distance | Predicted delivery distance |
| segment_actual_time | Delivery time for a segment |
| segment_osrm_time | Predicted segment time |
| segment_osrm_distance | Predicted segment distance |

---

## ⭐ STAR Framework

### Situation
Delhivery aims to optimize logistics operations and improve delivery efficiency using data analysis and feature engineering.

### Task
Analyze delivery data and identify patterns affecting route efficiency and delivery time.

### Action

- Performed data cleaning and preprocessing
- Converted timestamp columns to datetime format
- Engineered new features for trip-level analysis
- Aggregated route segments using groupby operations
- Conducted exploratory data analysis
- Compared actual vs predicted delivery metrics

### Result

- Identified busiest delivery corridors
- Observed differences between OSRM predicted routes and actual routes
- Provided insights for improving route planning and logistics efficiency
- Highlighted opportunities for improving delivery time accuracy

---

## 🛠 Tools Used

Python  
Pandas  
NumPy  
Seaborn  
Matplotlib  
Scikit-learn  

---

## 📂 Repository Files
