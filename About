#  Nepal Disaster Analytics Dashboard

## 📊 Power BI Disaster Analytics Project

Nepal Disaster Analytics is an interactive Power BI dashboard designed to analyze disaster incidents and their impacts across Nepal.

The dashboard provides insights into disaster incidents, deaths, injuries, missing people, houses affected and destroyed, infrastructure damage, livestock damage, economic losses, districts, provinces, hazards, disaster trends, and severity.

## 🎯 Project Objective

The main objective of this project is to transform disaster-related data into meaningful and interactive visual insights using Power BI.

The dashboard helps users explore disaster patterns and understand their impact through geographical, temporal, and severity-based analysis.

### The project focuses on:

- Disaster incident analysis
- District-wise analysis
- Province-wise analysis
- Disaster trends over time
- Death and injury analysis
- Missing people analysis
- House damage analysis
- Infrastructure damage analysis
- Livestock damage analysis
- Economic loss analysis
- Disaster severity analysis

## 🛠️ Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel
- Data Cleaning
- Data Transformation
- Data Modeling
- Data Visualization
- Exploratory Data Analysis

## 📌 Dashboard Pages

### 1. Nepal Disaster Overview

This page provides an overall summary of disaster incidents and their impacts.

### Key Performance Indicators

- Total Incidents
- Total Deaths
- Total Injured
- Total Missing
- Total Economic Loss
- Houses Destroyed

### Visualizations

- Total Incidents by Hazard
- Total Incidents Trend
- Total Deaths by Province
- Total Incidents by Severity

### Filters

- Date
- Province
- District
- Hazard

---

### 2. District & Province Analysis

This page focuses on geographical analysis of disaster incidents across districts and provinces.

### Visualizations

- Total Incidents by District
- Total Injured by District
- Total Deaths by District
- Houses Destroyed vs Houses Affected by Province
- District-wise Disaster Map

---

### 3. Disaster Trend Analysis

This page focuses on understanding disaster patterns over time.

### Visualizations

- Total Deaths by Year
- Total Injured by Year
- Total Missing by Year
- Total Incidents by Year
- Incidents Trend by Hazard

A dedicated date dimension is used for date-based analysis and filtering.

---

### 4. Infrastructure & Severity

This page focuses on physical damage, economic impact, and disaster severity.

### Key Performance Indicators

- Infrastructure Destroyed
- Houses Destroyed
- Houses Affected
- Livestock Destroyed
- Total Economic Loss
- Infrastructure Economic Loss

### Visualizations

- Houses Destroyed by Province
- Total Incidents by Severity

### Severity Categories

- Low
- Medium
- High
- Critical

## 📅 Data Modeling

A dedicated date dimension was created in Power BI using DAX.

```DAX
Dim_Date =
CALENDAR(
    MIN('incidents-wise'[Incident on]),
    MAX('incidents-wise'[Incident on])
)

## 📐 DAX Measures

### Total Incidents

```DAX
Total Incidents =
COUNTROWS('incidents-wise')
```

### Total Deaths

```DAX
Total Deaths =
SUM('incidents-wise'[Total - People Death])
```

### Total Injured

```DAX
Total Injured =
SUM('incidents-wise'[Total - People Injured])
```

### Total Missing

```DAX
Total Missing =
SUM('incidents-wise'[Total - People Missing])
```

### Houses Destroyed

```DAX
Houses Destroyed =
SUM('incidents-wise'[House destroyed])
```

### Houses Affected

```DAX
Houses Affected =
SUM('incidents-wise'[House affected])
```

### Total Economic Loss

```DAX
Total Economic Loss =
SUM('incidents-wise'[Total estimated loss (NPR)])
```

---

## 🚨 Disaster Severity Analysis

A custom severity classification was created to analyze the impact of individual disaster incidents.

The severity calculation considers:

* People Death
* People Missing
* People Injured
* Houses Destroyed
* Houses Affected
* Estimated Economic Loss

The dashboard categorizes incidents into four severity levels:

* Low
* Medium
* High
* Critical

This classification is used for interactive severity analysis in the Power BI dashboard.

---

## 🔍 Interactive Analysis

The dashboard provides interactive filtering through Power BI slicers.

Users can filter the dashboard using:

* Date
* Province
* District
* Hazard

When a filter is selected, the dashboard visuals and KPI cards update automatically.

---

## 🧹 Data Transformation

Data preparation and transformation were performed using Power Query.

The main transformation steps include:

1. Importing the disaster dataset
2. Cleaning the source data
3. Changing appropriate data types
4. Preparing date columns
5. Preparing numerical columns
6. Handling data required for analysis
7. Creating the required calculated fields
8. Loading the transformed data into the Power BI data model

---

## 📊 Dashboard Visualizations

The project uses different Power BI visuals to present the analysis:

* KPI Cards
* Bar Charts
* Column Charts
* Line Charts
* Donut Charts
* Maps
* Slicers

These visuals provide interactive analysis of disaster incidents and their impacts.

---

## 📈 Key Analysis Areas

The dashboard allows analysis of:

### Disaster Incidents

Analysis of the total number of disaster incidents.

### Human Impact

Analysis of:

* Deaths
* Injuries
* Missing people

### Geographical Impact

Analysis by:

* Province
* District

### Property Damage

Analysis of:

* Houses destroyed
* Houses affected
* Infrastructure destroyed

### Livestock Impact

Analysis of livestock destroyed.

### Economic Impact

Analysis of:

* Total estimated economic loss
* Infrastructure-related economic loss

### Severity

Analysis of incidents categorized as:

* Low
* Medium
* High
* Critical

### Time-Based Analysis

Analysis of disaster incidents and impacts over time using the dedicated date dimension.

---

## 📁 Project Files

The repository contains the following main folders:

```text
Nepal_Disaster_Analytics/
│
├── Dataset/
│
├── Power BI/
│
├── Screenshots/
│
└── README.md
```

### Dataset

Contains the source dataset used for the Power BI analysis.

### Power BI

Contains the Power BI `.pbix` dashboard file.

### Screenshots

Contains screenshots of the completed dashboard pages.

---

## 🚀 How to Use

### Step 1 — Download the Repository

Download or clone this repository from GitHub.

### Step 2 — Open Power BI

Open the `.pbix` file located inside the **Power BI** folder using Power BI Desktop.

### Step 3 — Check the Dataset

If Power BI asks for the dataset location, update the source path in Power Query.

### Step 4 — Refresh

In Power BI Desktop, select:

**Home → Refresh**

### Step 5 — Explore the Dashboard

Use the available slicers and visuals to explore:

* Disaster incidents
* Districts
* Provinces
* Human impact
* Property damage
* Economic losses
* Disaster trends
* Severity

---

## 💡 Skills Demonstrated

This project demonstrates practical skills in:

* Power BI
* Power Query
* DAX
* Data Cleaning
* Data Transformation
* Data Modeling
* Data Visualization
* Dashboard Development
* Exploratory Data Analysis
* KPI Development
* Time-Series Analysis
* Geographical Analysis

---

## 📷 Dashboard Screenshots

### Nepal Disaster Overview

![Nepal Disaster Overview](Screenshots/dashboard-overview.png)

### District & Province Analysis

![District and Province Analysis](Screenshots/district-analysis.png)

### Disaster Trend Analysis

![Disaster Trend Analysis](Screenshots/disaster-trends.png)

### Infrastructure & Severity

![Infrastructure and Severity](Screenshots/infrastructure-severity.png)

---

## 🎓 Project Purpose

This project demonstrates how disaster-related data can be transformed into an interactive Business Intelligence dashboard using Power BI.

The dashboard provides a structured way to explore disaster frequency, geographical distribution, human impact, infrastructure damage, economic loss, and disaster severity.

---

## 👩‍💻 Author

### Saheranjum Makandar

**B.Tech – Computer Science & Engineering (Data Science)**

### Areas of Interest

* Data Science
* Machine Learning
* Data Analytics
* Power BI
* SQL
* Python
* Data Visualization

---

## ⭐ Project

If you find this project useful, consider giving the repository a ⭐ star.

Thank you for visiting this project! 🇳🇵📊
