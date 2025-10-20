# 💳 Card Issuance per RM Dashboard

📊 **Project Overview**  
The **Card Issuance per RM Dashboard** project tracks and visualizes the quarterly performance of Relationship Managers (RMs) in issuing salary and corporate cards for newly onboarded corporates.

This dashboard evaluates how effectively each RM met the target of **750 cards per quarter**, analyzing **month-by-month performance** and **regional averages**.

The project follows the **data analytics life cycle**:  
**Business Understanding → Data Preparation → Analysis → Visualization → Insights**

---

## 📌 Table of Contents
1️⃣ [Business Understanding](#1-business-understanding)  
2️⃣ [Data Understanding](#2-data-understanding)  
3️⃣ [Approach (Data Analysis Life Cycle)](#3-approach-data-analysis-life-cycle)  
4️⃣ [Technologies](#4-technologies)  
5️⃣ [Setup](#5-setup)  
6️⃣ [Screenshots & Results](#6-screenshots--results)  
7️⃣ [Status](#7-status)

---

## 1️⃣ Business Understanding
- Objective: Track and evaluate RM performance in issuing salary and corporate cards.  
- Target: 750 cards per RM per quarter.  
- Key KPIs:
  - Cards issued per RM (monthly & quarterly)
  - % Achievement vs target
  - Regional performance averages
- Purpose: Enable **management reporting**, identify top performers, and pinpoint underperforming regions for targeted interventions.

---

## 2️⃣ Data Understanding
- **Data Sources**: Excel files from each branch, monthly RM reports.  
- **Data Fields**:
  - RM Name
  - Branch
  - Month
  - Cards Issued
  - Corporate Name
  - Employee Count
- **Data Quality Checks**:
  - Verify completeness and duplicates
  - Standardize naming conventions
  - Ensure monthly breakdowns match quarterly totals

---

## 3️⃣ Approach (Data Analysis Life Cycle)
### 3.1 Business Understanding
- Define RM performance KPIs and quarterly targets  
- Identify branch-level reporting needs  

### 3.2 Data Preparation
- Consolidate all branch files into a **master Excel file**  
- Clean and standardize RM names, corporate names, and dates  
- Add calculated fields:
  - `% Achievement = (Cards Issued / 750) * 100`  
  - `Variance = Cards Issued – 750`  

### 3.3 Analysis
- Compare RM performance against quarterly targets  
- Compute monthly averages and trends per region  
- Identify top and bottom performers  

### 3.4 Visualization
- **Power BI Dashboard** including:
  - Cards issued per RM (Bar/Column chart)  
  - % Achievement vs Target (Gauge/Donut chart)  
  - Regional averages (Map/Cluster chart)  
  - Monthly trend (Line chart)  

### 3.5 Insights
- Highlight high-performing RMs and regions  
- Identify areas needing support or training  
- Inform quarterly management reporting  

---

## 4️⃣ Technologies
- **Data Handling**: Excel, Power Query  
- **Visualization**: Power BI  

---
