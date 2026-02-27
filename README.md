### ecommerce-website-performance-behavioral-analysis-pbi

# Website Performance & User Behavior Overview

### **Project Background**

This project analyzes a comprehensive e-commerce dataset to evaluate scaling efficiency, user engagement, and conversion health. By processing large-scale traffic data, the primary goal was to transform raw session records into actionable insights regarding channel performance and funnel drop-offs. By identifying an overall **6.83% CVR** and an **Average Session Time of 10.82 minutes**, this analysis isolates high value traffic segments to guide marketing spend and site optimization.

**Insights and recommendations are provided on the following key areas:**

* **Conversion Optimization:** Evaluation of the 6.83% CVR across user types and repeat visits.
* **Traffic Acquisition:** Identifying the dominance of **gsearch** and **bsearch** in driving new user volume.
* **User Retention:** Analyzing the 72.55% single-visit majority vs. the higher CVR of repeat customers.
* **Behavioral Distribution:** Mapping the hourly traffic heat and pageview funnel from landing to confirmation.

![Dashboard Preview](https://github.com/afrinanegaban/ecommerce-website-performance-behavioral-analysis-pbi/blob/main/Image/Snapshot%20of%20Dashboard.png)

---

## **Data Structure & Model**

The project utilizes a relational schema optimized for high volume performance monitoring.

* **Website Sessions:** Tracks unique entries, traffic sources: gsearch, bsearch, social and direct(organic), and user types: New vs. Repeat.
* **Pageviews:** Logs 1.19M total views, categorized into functional groups like Product, Cart, and Billing.
* **Orders & Conversions:** Captures transaction success rates, including specific CVR benchmarks for repeat visitors.
* **Measures Table:** Centralized repository for KPIs including Bounce Rate (44.76%) and Avg Session Time.

![ERD](https://github.com/afrinanegaban/ecommerce-website-performance-behavioral-analysis-pbi/blob/main/Image/ERD.png)

---

## **Executive Summary**

### **Overview of Findings**

The platform currently sustains a healthy **6.83% Conversion Rate** with a strong user engagement baseline of **10.82 minutes per session**. While total pageviews have reached **1.19M**, the **44.76% Bounce Rate** indicates a critical need to optimize landing page relevance for new gsearch traffic. High value growth is found in repeat visitors, who exhibit a significantly higher CVR (7.8%) compared to new visitors (6.6%), suggesting that retention is the primary driver of long term profitability.

---

## **Insights Deep Dive**

### **Category 1: Traffic Growth & Acquisition**

* **Search Dominance:** **gsearch** is the primary traffic driver with 295K new sessions, significantly outperforming **bsearch** and **socialbook**.
* **Traffic Trends:** Long term analysis shows a massive volume surge peaking in late 2014, with monthly traffic consistently exceeding 50K sessions.
  
![category 1](https://github.com/afrinanegaban/ecommerce-website-performance-behavioral-analysis-pbi/blob/main/Image/Category%201.png)

### **Category 2: Conversion Performance & Benchmarking**

* **Conversion Floor:** The overall 6.83% CVR is a strong benchmark, but the data reveals a "Retention Premium", where users on their 2nd visit convert at **7.8%**.
* **Funnel Leakage:** The Pageview Distribution shows a steep drop from the **Landing Page (335.3K)** to **Order Confirmation (9.6%)**, identifying the Shipping and Billing pages as primary friction points.
  
![category 2](https://github.com/afrinanegaban/ecommerce-website-performance-behavioral-analysis-pbi/blob/main/Image/Category%202.png)

### **Category 3: User Behavior & Engagement**

* **Deep Engagement:** The **10.82-minute Average Session Time** suggests that users who don't bounce are highly engaged with product content.
* **Peak Activity:** The Hourly Traffic Distribution identifies **10:00 AM to 5:00 PM** as the peak window for user activity, particularly on weekdays.
  
![category 3](https://github.com/afrinanegaban/ecommerce-website-performance-behavioral-analysis-pbi/blob/main/Image/Category%203.png)

### **Category 4: Retention & Repeat Behavior**

* **Single Visit Dependency:** 72.55% of users are one-time visitors, highlighting a high cost of customer acquisition.
* **Repeat Value:** Although they represent a smaller segment, users with 2 or more visits show improved CVR, proving that remarketing efforts are high-ROI.
  
![category 4](https://github.com/afrinanegaban/ecommerce-website-performance-behavioral-analysis-pbi/blob/main/Image/Category%204.png)

---

## **Recommendations**

Based on the dashboard insights, I recommend the following:

1. **Optimize High-Volume Landing Pages:** Address the **44.76% Bounce Rate** by A/B testing the Landing Page (335.3K views) to ensure the 10.82-minute session depth is triggered earlier.
2. **Incentivize Repeat Visits:** Since CVR jumps to **7.8%** on the second visit, implement email triggers or "Save for Later" features to capture the 72.55% of users currently only visiting once.
3. **Targeted Ad Scheduling:** Align marketing spend with the **10:00-17:00** peak traffic window to maximize visibility during high-intent hours.
4. **Checkout Friction Audit:** Conduct a UX audit of the **Shipping and Billing pages**, as these represent the final barriers before the 9.6% conversion completion.

