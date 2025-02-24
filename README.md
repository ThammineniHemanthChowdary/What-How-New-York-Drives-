# **What, How, New York Drives? 🚗📊**

### **Project Overview**
This project analyzes **New York State's transportation dynamics** using **8.8 million vehicle transaction records**, **3.26 million crash records**, and **EV charging station data**. The goal is to understand **vehicle trends**, **road safety dynamics**, and **electric vehicle (EV) adoption**. The project utilizes **Tableau dashboards** to provide interactive visualizations for policymakers, transportation agencies, and the public.

### **Team Members**
- **Shoumik Reddy Kumbham**
- **Likith Kolli**
- **Hemanth Chowdary Thammineni**
- **Saurav Sundararaju Makam**
- **Goutham Sri Vishwesh Bikkumalla**

---

## **Table of Contents**
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Data Preprocessing](#data-preprocessing)
- [Insights from Dashboards](#insights-from-dashboards)
- [Future Work](#future-work)
- [Installation & Usage](#installation--usage)
- [Project Structure](#project-structure)
- [Acknowledgments](#acknowledgments)

---

## **Dataset Description**
The project utilizes **three primary datasets** from the **New York State Department of Motor Vehicles (NY DMV) and public data sources**:

1. **What New York Drives**
   - **Vehicle registrations and transactions data** (2023) from NY DMV.
   - Includes **8.8 million records** detailing **popular brands, vehicle body types, and registration trends**.
   - [Dataset Link](https://data.ny.gov/Transportation/Department-of-Motor-Vehicles-Registration-Transact/s2dd-yksa/about_data)

2. **How New York Drives**
   - **Motor vehicle crash data** (2018-2022).
   - Includes **3.26 million crash records**, covering **crash patterns, driver age groups, vehicle categories, and safety outcomes**.
   - [Dataset Link](https://data.ny.gov/Transportation/Motor-Vehicle-Crashes-Vehicle-Information-Three-Ye/xe9x-a24f/about_data)

3. **EV Adoption in New York**
   - **Electric vehicle (EV) charging station data** across New York.
   - Explores **EV infrastructure trends and adoption across different regions**.
   - [Dataset Link](https://data.ny.gov/Energy-Environment/Electric-Vehicle-Charging-Stations-in-New-York/7rrd-248n/about_data)

---

## **Data Preprocessing**
To ensure high-quality input for analysis, the following preprocessing steps were applied:

1. **Data Cleaning**
   - Removed **irrelevant columns** and **filtered necessary records**.
   - Addressed **missing values** using **imputation techniques**.

2. **Feature Engineering**
   - Categorized vehicle types, fuel types, and registration trends.
   - Mapped **crash severity, vehicle age, and safety trends**.
   - Identified **EV adoption growth by region**.

3. **Data Integration**
   - Merged datasets to enable **comparative analysis**.
   - Created **geospatial mappings** for transaction and crash densities.

---

## **Insights from Dashboards**
The project features **three key Tableau dashboards**:

### **1. What New York Drives? 🚘**
- **Analyzes 8.8 million DMV transactions (2023)**.
- Identifies **popular vehicle brands (Toyota, Honda, Chevrolet)**.
- Examines **fuel types, body types, and vehicle age trends**.
- Visualizes **transaction densities across ZIP codes**.

### **2. How New York Drives? 🚦**
- **Analyzes 3.26 million crash records (2018-2022)**.
- Examines **crash severity, driver demographics, and safety trends**.
- Highlights **crash hotspots and temporal trends (time of day, day of the week)**.
- Provides **insights into risk factors for different driver age groups**.

### **3. EV Adoption in New York 🔋⚡**
- **Explores electric vehicle growth and charging infrastructure**.
- Maps **EV charging stations by city and county**.
- Identifies **popular EV brands and regions leading adoption**.
- Analyzes **charging station distribution for sustainable transportation planning**.

---

## **Future Work**
1. **Enhancing Predictive Analytics**
   - Use **machine learning models** to predict **future EV adoption rates and crash probabilities**.
   - Analyze **emerging trends in vehicle electrification**.

2. **Real-Time Data Integration**
   - Implement **live crash tracking and registration updates**.
   - Integrate **real-time vehicle transaction monitoring**.

3. **Policy Recommendations**
   - Provide insights for **sustainable transportation planning**.
   - Identify **safety improvement measures** based on crash trends.

---

## **Installation & Usage**
### **Prerequisites**
- **Tableau** (for viewing dashboards)
---

## **Project Structure**
```
📂 NY-Transportation-Analysis
│── 📄 README.md                      # Project Documentation
│── 📄 VAD_Group2_Final_Report.pdf    # Detailed Report
│── 📄 Tableau_Dashboards/            # Tableau Dashboard Files
```

---

## **Acknowledgments**
This project was developed as part of **IST 737: Visual Analytic Dashboards** at **Syracuse University**, under the guidance of **Professor Raj Dewan**.
