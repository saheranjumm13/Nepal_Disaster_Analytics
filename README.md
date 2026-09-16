# 🇳🇵 Nepal Disaster Analytics Dashboard

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
