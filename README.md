# 🧘 Wellness & Healthcare App User Analytics Dashboard

## 📊 Project Overview
This repository contains a comprehensive, multi-page Power BI dashboard engineered to analyze user engagement and predict churn factors for a modern digital healthcare and wellness application. The project translates raw behavioral telemetry from **1,000 users** into actionable business insights focused on increasing user retention and maximizing subscription tier value.

### 🔗 Live View / Files Included
* **[View Dashboard File](./Healthcare_Wellness_Dashboard.pbix)**
* **Dataset Used:** `calm_sleep_CLEANED.csv`

---

## 🚀 Key Business Questions Answered
1. **Engagement Optimization:** Which subscription models yield the highest meditation minutes?
2. **Platform Distribution:** How does our user base split across iOS and Android ecosystems?
3. **Churn Mitigations:** What core behavioral trends (sleep tracking, app engagement) signal that a user is about to leave?

---

## 🖥️ Dashboard Architecture & Features

### 📱 Page 1: User Engagement Overview
Focuses on baseline performance indicators, tracking active demographics and product tier usage.
* **Key Visuals:** Balanced KPI tracking cards (Total Users, Average Age, Baseline Churn Rate), an interactive Gender-segmented slicer panel, a matrix crossing OS vs. Subscription tier, and a smoothed multi-line trend chart showing Sleep Tracking Consistency across various ages.
* **Visual Polish:** Fully custom high-contrast dark theme optimized for modern dark-mode application standards.

### 📉 Page 2: Churn & Predictive Insights Portal
Deploys exploratory data structures to isolate risk patterns among inactive users.
* **Key Visuals:** A demographic **Scatter Chart** clustering active vs. churned users by age and meditation frequency, an behavioral **Clustered Bar Chart** analyzing the direct link between tracking gaps and subscriber loss, and a **Matrix Heatmap** mapping platform-specific revenue risk intersections.

---

## 💡 Strategic Data Insights
* **The Meditation Threshold:** Scatter clustering reveals a significant churn trend among users averaging under 40 minutes of meditation per month, regardless of tier.
* **Habit-Forming Retention:** Users who consistently engage with the sleep tracker for more than 15 days a month display a **60% lower churn rate** compared to low-frequency trackers.

---

## 🔧 Technical Tool Stack
* **BI Platform:** Power BI Desktop
* **Data Transformation:** Power Query (Data cleaning, handling null values, data type formatting)
* **Design Principles:** Clean grid design layout, transparent visual backgrounds, customized high-visibility series color palettes for cross-tier visibility.
