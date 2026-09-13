# EDA-Project
# 🚗 Indian Road Accident Analysis – EDA

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on an Indian road accident dataset to understand accident patterns, severity, causes, locations, time-related trends, casualties, and risk scores.

The goal of this project is to extract meaningful insights from accident data that can help in understanding important road safety patterns.

---

## 🎯 Objectives

- Understand the structure and characteristics of the dataset
- Analyze accident distribution across cities and states
- Identify the most common accident causes
- Analyze accident severity
- Study accident patterns by day, month, and hour
- Compare weekday and weekend accidents
- Analyze peak and non-peak hour accidents
- Understand the relationship between vehicles involved and casualties
- Analyze accident risk scores
- Identify important correlations between numerical variables
- Generate meaningful insights from the data

---

## 📊 Dataset

The dataset contains **20,000 accident records** and **24 columns**.

### Main Features

| Feature | Description |
|---|---|
| `accident_id` | Unique accident identifier |
| `city` | City where the accident occurred |
| `state` | State where the accident occurred |
| `latitude` | Accident latitude |
| `longitude` | Accident longitude |
| `date` | Date of accident |
| `time` | Time of accident |
| `hour` | Hour of the accident |
| `day_of_week` | Day of the week |
| `is_weekend` | Indicates weekend or weekday |
| `road_type` | Type of road |
| `lanes` | Number of lanes |
| `traffic_signal` | Traffic signal condition |
| `weather` | Weather condition |
| `visibility` | Visibility condition |
| `temperature` | Temperature |
| `traffic_density` | Traffic density |
| `cause` | Main cause of accident |
| `accident_severity` | Accident severity |
| `vehicles_involved` | Number of vehicles involved |
| `casualties` | Number of casualties |
| `is_peak_hour` | Indicates peak hour |
| `festival` | Festival information |
| `risk_score` | Accident risk score |

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Google Colab**

---

## 🔍 Analysis Performed

### 1. Data Understanding

- Dataset shape
- Data types
- Statistical summary
- Initial data inspection

### 2. Data Cleaning

- Missing value analysis
- Duplicate record checking
- Data type checking

### 3. Univariate Analysis

Analyzed:

- Accidents by city
- Accidents by state
- Accident severity
- Accident causes
- Weather conditions
- Traffic density
- Road types
- Day of week
- Peak vs non-peak hours

### 4. Bivariate Analysis

Analyzed relationships between:

- Cause vs accident severity
- Traffic density vs accident severity
- City vs accident severity
- Road type vs accident severity
- Vehicles involved vs accident severity
- Vehicles involved vs casualties

### 5. Time-Based Analysis

- Accidents by hour
- Accidents by month
- Weekday vs weekend accidents
- Peak vs non-peak accidents

### 6. Risk Analysis

- Risk score distribution
- Risk score by accident severity
- Average risk score by city
- Average risk score by accident cause

### 7. Correlation Analysis

A correlation heatmap was used to identify relationships between numerical variables.

---

## 💡 Key Findings

- **Minor accidents** were the most common, accounting for **55.125%** of accidents.
- **Major accidents** accounted for **29.940%**.
- **Fatal accidents** accounted for **14.935%**.
- **Distraction and overspeeding** were among the most frequent accident causes.
- **Monday** recorded the highest number of accidents among the days of the week.
- **Wednesday** recorded the lowest number of accidents among the days analyzed.
- **Weekdays** had more accidents than weekends.
- **Maharashtra** recorded the highest number of accidents among the states in the dataset.
- **January and March** recorded comparatively higher accident counts.
- Accidents involving more vehicles generally showed a tendency toward higher casualties.
- Fatal accidents had the **highest average casualties**, approximately **3.00**.
- Fatal accidents generally had higher risk scores than major and minor accidents.
- The correlation between **vehicles involved and casualties** was approximately **0.55**, indicating a moderate positive relationship.
- Average risk scores were very similar across cities and accident causes.

---

## 📈 Conclusion

The EDA provided useful insights into road accident patterns in India. The analysis showed that accident severity, causes, location, time, number of vehicles involved, and casualties are important factors for understanding accident patterns.

Minor accidents formed the largest proportion of the dataset, while fatal accidents had a higher average number of casualties and generally higher risk scores. The analysis also identified overspeeding and distraction as important accident causes.

Overall, this project demonstrates how **Python-based exploratory data analysis** can be used to clean, analyze, visualize, and extract meaningful insights from a real-world dataset.

---

## 👨‍💻 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Statistical Analysis
- GroupBy and Aggregation
- Correlation Analysis
- Python Programming
- Pandas & NumPy
- Matplotlib & Seaborn
- Insight Generation
