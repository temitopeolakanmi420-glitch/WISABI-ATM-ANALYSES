# 🏧 Wisabi ATM Performance & Customer Demographics Analysis

An interactive 2-page Power BI business intelligence project evaluating **2 Million transactions** valued at **₦39 Billion** across a Nigerian ATM network. This project uncovers regional utilization bottlenecks, operational durations, and customer demographic trends to optimize cash management and machine placement[cite: 3, 4].

---

## 📋 Table of Contents
- [Project Overview](#-project-overview)
- [Executive Summary & Key Metrics](#-executive-summary--key-metrics)
- [Business Problems Identified](#-business-problems-identified)
- [Dashboard Preview & Visual Explanations](#-dashboard-preview--visual-explanations)
- [Strategic Business Recommendations](#-strategic-business-recommendations)
- [Tools & Technologies](#-tools--technologies)

---

## 🔍 Project Overview
Managing an ATM network efficiently requires tracking cash flow, customer behavior, and hardware performance. This project integrates multiple transaction files, customer demographics, and calendar data into a robust relational model to answer key operational questions:
* *Where is cash demand highest across different states[cite: 3]?*
* *Which customer demographics and transaction types drive system usage[cite: 4]?*
* *How can operational bottlenecks and long transaction durations be minimized[cite: 3, 4]?*

---

## 📊 Executive Summary & Key Metrics
* **Total Transaction Value**: ₦39 Billion[cite: 3]
* **Total Transaction Volume**: 2 Million Transactions[cite: 3]
* **Total Customer Base**: 8,819 Active Customers[cite: 3]
* **Overall Utilization Rate**: 12.9%[cite: 3]

---

## 🚨 Business Problems Identified
1. **Low Overall Utilization Rate (12.9%)**: System-wide utilization is relatively low compared to total installation capacity, indicating idle or misplaced terminals[cite: 3].
2. **Geographic Skewness**: Utilization is heavily concentrated in specific regions—such as **Kano (18.6%)** and **Rivers State (12.7%)**—leaving other areas like **FCT (8.5%)** underutilized[cite: 3].
3. **Transaction Duration Bottlenecks**: Certain states and transaction types experience extended processing durations, impacting terminal throughput and customer wait times[cite: 3, 4].
4. **Demographic Concentration**: Younger adult brackets (**16–35**) dominate cash withdrawals, suggesting an opportunity to push digital or mobile alternatives for routine transactions[cite: 4].

---

## 📷 Dashboard Preview & Visual Explanations

### Page 1: ATM Operational & Geographic Analysis
This page focuses on spatial distribution, hourly traffic patterns, and state-level performance[cite: 3].

!### Page 1: ATM Operational & Geographic Analysis
[![Page 1 Overview](screenshots/Screenshot%202026-10-12%20231632.png)](YOUR_PUBLISH_TO_WEB_URL_HERE)


* **Hourly Trends & Location Performance**: Tracks how transaction counts fluctuate between 6:00 AM and 9:00 PM across different regions[cite: 3].
* **State Utilization Breakdown**: Highlights regional share, showing Kano leading at 18.6% utilization and 8,819 active customers[cite: 3].
* **Duration vs. Amount Scatter Plot**: Evaluates operational efficiency by mapping average transaction amounts against processing durations across states[cite: 3].
* **Monthly Volume Trends**: Monitors transaction volume and cash value trends across the calendar year[cite: 3].

---

### Page 2: Customer Demographics & Behavior Analysis
This page explores customer segments, age brackets, and transaction behaviors[cite: 4].

### Page 2: Customer Demographics & Behavior Analysis
[![Page 2 Overview](screenshots/Screenshot%202026-10-12%20231530.png)](YOUR_PUBLISH_TO_WEB_URL_HERE)


* **Transaction Type Share**: Highlights that **Withdrawals (55.5% / 1.19M)** and **Transfers (22.2% / 476K)** make up the vast majority of activities, alongside Deposits and Balance Inquiries[cite: 4].
* **Age Group Distribution**: Shows peak transaction frequencies concentrated among customers aged **16–35**[cite: 4].
* **Decomposition Tree**: Maps transaction paths through customer occupations (Students, Health Professionals, Traders)[cite: 4].
* **Duration by State & Type**: Compares processing times across various transaction types per state[cite: 4].

---

## 💡 Strategic Business Recommendations

1. **Optimize Cash Replenishment Schedules**: 
   * Prioritize morning and mid-day cash stocking in high-volume regions like Kano and Lagos to prevent terminal downtime during peak hours (9:00 AM – 3:00 PM)[cite: 3].
2. **Relocate Underperforming Terminals**: 
   * Move idle or low-utilization terminals from lower-performing areas (such as FCT at 8.5%) to high-demand commercial hubs or university campuses[cite: 3].
3. **Streamline High-Duration Transactions**: 
   * Optimize UI flows for cash transfers and deposits to decrease terminal dwell time and clear queues faster[cite: 3, 4].
4. **Drive Digital Migration**: 
   * Leverage the high volume of younger users (ages 16–25 and 26–35) doing basic withdrawals to promote mobile banking apps, reducing physical branch congestion[cite: 4].

---

## 🛠️ Tools & Technologies
* **Power BI Desktop**: Data modeling, measure creation, and interactive visual design[cite: 3, 4].
* **Power Query**: Ingesting, cleaning, and appending multi-file transaction logs.
* **GitHub**: Version control and portfolio presentation.
