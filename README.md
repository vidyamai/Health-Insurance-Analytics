# Shield Insurance Analysis

## Table of Contents
- [About Shield Insurance Company](#about-shield-insurance-company)
- [Project Background](#project-background)
- [Executive Summary](#executive-summary)
- [Insights Deep-Dive](#insights-deep-dive)
  - [Revenue & Customer Growth Analysis](#revenue--customer-growth-analysis)
  - [Sales Mode Analysis](#sales-mode-analysis)
  - [Age Group Analysis](#age-group-analysis)
- [Recommendations](#recommendations)

## About Shield Insurance Company

Shield Insurance Company is a leading provider of insurance solutions, offering a wide range of policies tailored to meet customer needs. This project focuses on analyzing key revenue and customer growth metrics for Shield Insurance to track trends, identify areas for improvement, and enhance decision-making.

## Project Background

The primary objective of this project is to **understand the number of customers and the total revenue generated** over a defined period. Additionally, it aims to:

- Track **daily revenue and customer growth rates** to monitor progress.
- Analyze **month-over-month policy changes** to identify trends.
- Segment customers by **age group** and analyze revenue and customer distribution by **city and age group**.
- Provide **interactive trend visualizations** with a switch between revenue and customer growth graphs.
- Enable **filter-based analysis** for sales mode, age group, city, month, and policy ID.
- Create dedicated pages for **sales mode analysis** and **age group analysis** to provide deeper insights.

## Executive Summary

- **Total revenue from Dec 2022 to Apr 2023**: \$989.25M, with **March contributing the highest at \$256M**.
- **Delhi led in revenue**: \$402M from **11K customers**.
- **Offline-agent sales mode** generated the highest revenue: \$551M, **122% above the average**.
- **31-40 age group** contributed the most revenue: \$351M, while the **65+ age group had the lowest engagement**.
- **Policy trends**: POL3309HEL was the most frequent policy for **31-40 age group**, POL4321HEL for **18-30 age group**.

---

## Data Model
The data was structured using a star schema model to optimize performance and ease of analysis.

### Dimension Tables:
- **Date:** Calendar dates for analysis
- **Policies:** Details of insurance policies
- **Customers:** Information about customers

### Fact Tables:
- **Premiums:** Data on insurance premiums
- **Settlements:** Information on claim settlements

  ![image](https://github.com/vidyamai/Health-Insurance-Analytics/assets/84960322/800aa589-eb59-459e-885c-d6331d5a4239)

## Insights Deep-Dive

### **Revenue & Customer Growth Analysis**

![image](https://github.com/vidyamai/Health-Insurance-Analytics/assets/84960322/f5858d8f-8022-4853-8b8d-5d1bc60f78ec)

- The **total revenue from December 2022 to April 2023** was **\$989.25 million**.
- **March recorded the highest revenue** at **\$256 million**. However, due to limited data, the exact reason for this sudden surge remains unclear.
- **Delhi**, being a major metro city, led the revenue charts, contributing **\$402 million** with **11,000 customers**.

### **Sales Mode Analysis**

![image](https://github.com/vidyamai/Health-Insurance-Analytics/assets/84960322/1d5ddae8-217b-4a43-8993-c2f8b2befb07)

- **Offline-agent sales mode** dominated with **\$551 million in revenue**, which is **122% higher than the average across all sales modes**.
- **Online website sales mode** generated the **least revenue**, indicating potential areas for marketing improvements or user experience enhancements.

### **Age Group Analysis**

![image](https://github.com/vidyamai/Health-Insurance-Analytics/assets/84960322/f33270ec-635f-4677-abdb-cb4c0ec6b56c)


- The **31-40 age group** contributed the highest revenue at **\$351 million**, showcasing strong insurance adoption in this demographic.
- The **65+ age group** had the **lowest revenue generation**, despite a higher perceived need for insurance, requiring further investigation.
- The **most frequently purchased policy for the 31-40 age group** was **POL3309HEL**, while the **18-30 age group preferred POL4321HEL**.

---

## Recommendations

Based on the analysis, the following actions are recommended:

1. **Investigate the surge in March revenue** by analyzing customer acquisition strategies, marketing campaigns, and external market factors.
2. **Enhance online sales mode strategies** through targeted digital marketing, improved customer education, and streamlined policy purchase flows.
3. **Explore engagement opportunities for the 65+ age group**, such as tailored insurance products, incentives, or awareness campaigns.
4. **Leverage high-performing age groups (31-40) with personalized offers and loyalty programs** to drive long-term retention.
5. **Analyze policy trends further** to understand why certain policies are more popular among specific age groups and optimize product offerings accordingly.

---

This project provides actionable insights into **revenue trends, customer growth, sales mode efficiency, and demographic-based purchasing behaviors**. Future analyses can focus on deeper segmentation, competitive benchmarking, and policy profitability assessments to drive sustained business growth.






