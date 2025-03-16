# NYC Road Safety Analysis: Identifying and Mitigating Motor Vehicle Collision Hotspots

## 📌 Project Overview  
This project analyzes motor vehicle collisions in New York City (NYC) to identify high-risk areas, contributing factors, and trends related to road safety. Using real-world data from **NYC Open Data**, we examine collision hotspots, time-based variations, vehicle involvement, and demographic correlations to propose actionable insights for improving road safety.

## 📈 Motivation  
NYC experiences high traffic-related fatalities and injuries due to congestion, road conditions, and driver behavior. By understanding the **patterns and factors contributing to collisions**, this project aims to:
- Identify high-risk areas and provide data-driven safety recommendations.
- Assist city planners and law enforcement in making informed decisions.
- Improve pedestrian and cyclist safety through targeted interventions.
- Support policymakers in setting regulations for safer roads.

## 📊 Research Questions  
The analysis addresses key road safety questions:
1. **Which NYC boroughs have the highest number of collisions?**  
2. **What time of day do most collisions occur?**  
3. **What are the top 5 vehicle types involved in collisions?**  
4. **What are the common contributing factors to collisions?**  
5. **How do injuries and fatalities vary among pedestrians, cyclists, and motorists?**  
6. **What is the monthly variation in collision rates?**  
7. **How do demographic patterns relate to collision data across boroughs?**

## 🗂️ Dataset  
The dataset used in this project is sourced from **NYC Open Data**, maintained by the **New York City Police Department (NYPD)**. It includes **over 2 million records** with key attributes such as:
- **Date & Time**: When the collision occurred.  
- **Location**: Borough, zip code, and street details.  
- **Casualties**: Number of injured/killed pedestrians, cyclists, and motorists.  
- **Contributing Factors**: Reasons for the crash (e.g., driver distraction, failure to yield).  
- **Vehicle Type**: Type of vehicles involved (e.g., Sedan, Taxi, SUV).  

🔗 **Data Source**: [NYC Open Data - Vision Zero Initiative](https://www1.nyc.gov/content/visionzero/pages/)

## 🔍 Methodology  

### 1️⃣ Data Cleaning & Preprocessing  
- Removed irrelevant columns (e.g., secondary contributing factors).  
- Handled missing values and standardized date/time formats.  
- Converted categorical data for numerical analysis.  

### 2️⃣ Exploratory Data Analysis (EDA)  
- Identified borough-wise collision trends.  
- Analyzed accident timing patterns.  
- Found correlations between vehicle types and collisions.  
- Visualized monthly variations in collision rates.  

### 3️⃣ Statistical & Outlier Analysis  
- Computed summary statistics for injuries and fatalities.  
- Used **Z-score** and **Interquartile Range (IQR)** methods to detect outliers.  

### 4️⃣ Geospatial & Demographic Analysis  
- Mapped collision density using **GeoPandas**.  
- Merged demographic data (e.g., population density) with accident rates.  
- Analyzed safety disparities across boroughs.  

## 📌 Key Findings  

- **Brooklyn and Queens have the highest number of collisions**, followed by Manhattan and The Bronx.  
- **Most collisions occur during rush hours (3 PM - 6 PM)** when traffic is at its peak.  
- **Sedans, SUVs, and taxis** are the most common vehicle types involved in collisions.  
- **Driver inattention/distraction is the leading cause of collisions**, followed by failure to yield and following too closely.  
- **Brooklyn has the highest number of pedestrian, cyclist, and motorist casualties**, while Staten Island has the lowest.  
- **Collisions peak in summer (June - August) and drop in winter (January - February).**  

## 📌 Visualizations  
The project includes various visualizations, such as:  
✅ **Bar charts** (Collision frequency by borough, contributing factors).  
✅ **Line charts** (Time-based trends, monthly variations).  
✅ **Heatmaps** (Accident density).  
✅ **Geospatial maps** (Collision distribution and demographic correlations).  

## 🚀 Technologies Used  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, GeoPandas)  
- **Data Visualization** (Matplotlib, Seaborn, Plotly)  
- **Geospatial Analysis** (GeoPandas, Folium)  
- **Jupyter Notebook**  

## 📌 Future Improvements  
🔹 Use **Machine Learning models** to predict accident-prone areas.  
🔹 Enhance demographic analysis with **census and socioeconomic data**.  
🔹 Explore **real-time crash data** for better traffic management.  

## 📜 Conclusion  
This project provides **actionable insights for improving road safety** in NYC. By identifying **collision hotspots, risk factors, and demographic correlations**, policymakers and city planners can **develop targeted interventions to reduce traffic accidents and enhance urban mobility.**  
