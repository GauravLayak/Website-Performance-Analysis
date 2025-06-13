# 📊 **Website Performance Analysis Report**

---

## 1. 🔍 **Project Overview**

**Objective**:
To analyze website traffic and user engagement across marketing channels using Google Analytics data, and identify actionable insights to optimize marketing strategies and content delivery.

**Tools Used**:

* Python: Pandas, Seaborn, Matplotlib
* Dataset: data export (CSV)
* Skills: EDA, data visualization, KPI analysis, business insights

---

## 2. 🎯 **Business Questions Addressed**

1. What trends exist in sessions and users over time?
2. Which marketing channels bring in the most users?
3. Which channel has the highest average engagement time?
4. How does engagement rate differ across channels?
5. What are the peak hours of activity for each channel?
6. Are higher traffic levels linked to higher engagement?
7. How do engaged vs. non-engaged sessions vary by channel?

---

## 3. 🧼 **Data Preparation**

* Cleaned and restructured raw CSV: set headers, dropped empty rows, parsed datetime.
* Converted key columns to numeric types for accurate aggregation.
* Created new column for `Hour` to enable time-based analysis.

---

## 4. 📈 **Key Visual Insights**

### 🔹 Sessions & Users Over Time

* **Line plot** shows consistent traffic growth across days.
* **Spikes in user activity** align with marketing pushes or peak browsing hours.

### 🔹 Total Users by Channel

* **Direct** and **Organic Search** are the top channels by user count.
* **Social** and **Email** have smaller reach but different engagement dynamics.

### 🔹 Average Engagement Time by Channel

* **Email** and **Referral** drive deeper engagement.
* Suggests high-quality or targeted content in those channels.

### 🔹 Engagement Rate Distribution

* Boxplot analysis shows **Referral** and **Email** have tight and high engagement.
* **Paid Search** and **Social** have wider variability.

### 🔹 Engaged vs. Non-Engaged Sessions

* Visualized split by channel.
* **Email** and **Referral** have higher ratios of engaged sessions.
* Opportunity to **improve engagement in Paid and Organic Search**.

### 🔹 Hourly Traffic by Channel

* Traffic peaks vary: **Social** peaks in evening, **Direct** in morning/afternoon.
* Suggests optimal **content scheduling strategies** by channel.

---

## 5. 💡 **Key Findings & Insights**

* **Direct and Organic Search** drive the most users, but **Email** and **Referral** drive the **most engaged sessions**.
* Engagement **doesn’t directly correlate with traffic volume** — highlighting the need to focus on content quality.
* Peak traffic hours vary by channel — scheduling posts accordingly can improve visibility and conversion.
* **Social** has low engagement despite traffic — suggest testing new post formats or landing pages.
* Channels with low engagement can benefit from **A/B testing** and personalized content.

---

## 6. 📌 **Recommendations**

* **Retarget** users from low-engagement channels with personalized campaigns.
* **Schedule content** for each channel during its respective peak hours.
* **A/B test landing pages** for Organic and Paid Search to improve engagement rates.
* **Leverage Email and Referral traffic** for long-form, high-retention content strategies.
