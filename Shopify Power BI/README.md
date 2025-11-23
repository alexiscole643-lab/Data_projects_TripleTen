# 📊 Power BI Project: Shopify App Success Analysis

## Overview
This project analyzes the Shopify App Store ecosystem using **Power BI** to uncover the key factors that contribute to an app’s success. By exploring app attributes, review patterns, developer responsiveness, and category distributions, the project provides data-driven insights that help identify high-performing apps and opportunities for improvement.

## 🔍 Project Objectives
- Understand the landscape of Shopify apps through KPIs, time-based trends, and rating distributions.  
- Evaluate user review behavior, including helpfulness scores and developer response patterns.  
- Identify top developers and categories using aggregated and weighted performance metrics.  
- Build interactive visualizations that support strategic decision-making for app creators and platform stakeholders.

## 📁 Dataset
**shopify.xlsx**  
Includes four joined tables:
- **apps** – core app details (ratings, installs, developer, last modified date, etc.)  
- **reviews** – individual user reviews, ratings, and developer replies  
- **categories** – list of all app categories  
- **apps_categories** – join table connecting apps to multiple categories  

## 🧠 Key Analyses & Visuals
### **1. App Landscape (Page 1)**
- KPI card showing total unique apps  
- Line chart showing review volume trends over time  
- Scatterplot comparing review count and average rating, with insights annotation  

### **2. Reviews Analysis (Page 2)**
- DAX-calculated **helpful_reviews** metric and KPI card for its average  
- DAX-calculated **developer_answered** indicator  
- Scatterplot comparing average rating vs. developer responsiveness  

### **3. App Reviews & Developer Performance (Page 3)**
- Relationship created between **Apps** and **Reviews** via `app_id`  
- Bar chart ranking developers by total ratings  
- Bar chart ranking developers by **average helpful_review**  
- Visualization showing developer responsiveness (filtered to apps with >500 reviews)  

## 🛠️ Tools Used
- **Microsoft Power BI**  
- **DAX (Data Analysis Expressions)**  
- **Data Modeling (many-to-one relationships)**  

## 📸 Deliverables
The final submission includes:
- Power BI report with **3 organized pages**  
- **8 full-screen screenshots** (one per question requirement)  
- All DAX formulas, data model relationships, and visual configurations applied  

## 🚀 Outcome
Through Power BI dashboards and calculated insights, this project reveals how reviews, helpfulness, developer engagement, and app characteristics influence overall app performance on Shopify. These findings support better strategic decisions for app developers, product teams, and marketplace analysts.

---
If this project is published on Power BI Service or GitHub in the future, you can insert your link below:

**🔗 Project Link:** _Coming soon_

