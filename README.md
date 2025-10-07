# 📊 Meta Ads Performance Analysis | Power BI Project

## 🧾 Project Overview
This Power BI project provides a comprehensive analysis of **Meta (Facebook & Instagram) Ad Performance**, focusing on campaign reach, engagement, and conversions.
It helps marketing teams identify high-performing ad formats, target audiences, and optimize ad budgets through interactive, data-driven dashboards.

The dashboard delivers a complete **marketing funnel view** — from impressions to purchases — helping decision-makers enhance campaign efficiency and ROI.



## 🎯 Business Objectives
- Evaluate campaign effectiveness across **Facebook and Instagram**.
- Measure **reach, engagement, and conversion efficiency**.
- Identify top-performing **ad types, demographics, and regions**.
- Optimize **ad scheduling and budget allocation** based on performance trends.

---

## 📌 Key Performance Indicators (KPIs)

| KPI | Description |
|------|--------------|
| **Impressions** | Total ad views across all campaigns |
| **Clicks** | Number of user clicks on ads |
| **CTR (Click-Through Rate)** | % of impressions that led to clicks |
| **Engagement Rate** | % of users who interacted (clicks, shares, comments) |
| **Purchases (Conversions)** | Total successful conversions |
| **Conversion Rate** | % of clicks resulting in purchases |
| **Purchase Rate** | % of impressions leading to purchases |
| **Total Budget** | Total ad spend across campaigns |
| **Avg. Budget per Campaign** | Mean budget allocated per campaign |

---

## 📈 Dashboard Insights

### 🔹 Funnel Analysis
- **216K Impressions → 25.4K Clicks → 1.3K Purchases**
- **CTR:** 11.76% (excellent) | **Engagement Rate:** 13.56% | **Conversion Rate:** 5.21%
💡 *Strong awareness and engagement, but lower purchase efficiency — optimize retargeting and landing pages.*

### 🔹 Audience Analysis
- **Gender:** Female engagement (43%) > Male (22%)
- **Age Group:** 18–30 drives highest interactions
💡 *Target young female audiences for volume and tailor premium campaigns for Europe.*

### 🔹 Ad Type & Timing
| Ad Type | CTR | Conversion Rate | Engagement Rate |
|----------|------|------------------|----------------|
| **Video** | 11.9% | 5.2% | 13.7% |
| **Stories** | 11.8% | 5.2% | 13.6% |
| **Carousel** | 11.7% | 5.1% | 13.4% |
| **Image** | 11.7% | 4.9% | 13.5% |

💡 *Video and Story ads deliver the best performance. Schedule ads in afternoons and evenings for higher engagement.*

---

## 🧱 Project Components

- **Data Source:** Meta Ads Data (Facebook & Instagram) 
- **Data Model:** Star Schema
  - Fact Table → `ad_events`
  - Dimensions → `ads`, `campaigns`, `users`
- **DAX Measures:** CTR, Conversion Rate, Engagement Rate, ROAS
- **Filters:** Platform, Ad Type, Gender, Age
- **Visuals:**
  - Donut Chart → Engagement by Gender
  - Bar Chart → Engagement by Age Group
  - Map → Country-wise Reach
  - Calendar Heatmap → Monthly Activity
  - Line Chart → Hourly Trends
  - Matrix → Ad Type vs Platform


## 🧠 Key Insights & Recommendations
1. Strong engagement but conversion leakage → focus on landing page & offers.
2. Female audiences aged **18–30** are most responsive.
3. Allocate higher budget to **Video & Story Ads**.
4. Best performance during **afternoons & evenings**.


---

## ⚙️ Tools & Technologies
- **Power BI Desktop** – Dashboard creation
- **Power Query** – Data transformation
- **DAX (Data Analysis Expressions)** – Custom KPI formulas

---

## 🖼️ Dashboard Preview

### Facebook Dashboard
![Facebook Dashboard](https://github.com/Subhasree05/Meta-ads-performace-dashboard-using-PowerBI/blob/main/Images/facebook%20dashboard.png)

### Instagram Dashboard
![Instagram Dashboard](https://github.com/Subhasree05/Meta-ads-performace-dashboard-using-PowerBI/blob/main/Images/instagram%20dashboard.png)



