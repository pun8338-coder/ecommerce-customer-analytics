# ecommerce-customer-analytics
## Executive Summary
This project delivers an end-to-end customer analytics pipeline and interactive Power BI dashboard evaluated on transaction-level e-commerce data. By applying **RFM (Recency, Frequency, Monetary) Scoring** and **Cohort Analysis**, this project translates raw transactional records into actionable behavioral insights for customer retention and marketing ROI optimization.
## Key Performance Indicators (KPIs)
* **Total Revenue:** $8.91M
* **Total Completed Orders:** 18,532
* **Unique Customers:** 4,338
* **Core VIP Revenue Contribution:** $6.84M (~76.8% of total revenue driven by 1,268 VIP customers)
* ## Dashboard Visual Previews

### 1. Executive Dashboard Overview (Unfiltered)
![Dashboard Overview](./screenshots/overview.png)

### 2. RFM Segment Distribution View
![RFM Segments](./screenshots/rtm_segments.png)

### 3. Segment Revenue Contribution View
![Segment Revenue](./screenshots/segment_revenue.png)

### 4. Customer-Level Table Preview
![Customer Details](./screenshots/customer_details.png)
## Customer Segment Distribution

| RFM Segment | Customer Count | Base Percentage | Business Focus & Action |
| :--- | :--- | :--- | :--- |
| **Lost / Hibernating** | 1,290 | 29.76% | Automated low-cost win-back email sequences |
| **VIP / Champions** | 1,268 | 29.23% | Loyalty rewards, early product access, VIP concierge |
| **At-Risk / Need Attention** | 940 | 21.58% | Re-engagement offers before complete churn |
| **Loyal Customers** | 840 | 19.43% | Cross-selling and upselling higher-margin products |
## Repository Structure
```text
RFM-Customer-Segmentation-PowerBI/
│
├── data/
│   ├── online_retail_cleaned.csv         # Cleaned transactional dataset
│   └── rfm_segments.csv                  # RFM scores & segment classifications
│
├── dashboard/
│   ├── Customer_Analytics_Dashboard.pbix # Source Power BI file
│   └── Dashboard_Export.pdf              # Exported static PDF report
│
├── screenshots/
│   ├── overview.png                      # Full dashboard overview screenshot
│   ├── rtm_segments.png                  # RFM segments distribution screenshot
│   ├── segment_revenue.png               # Segment revenue breakdown screenshot
│   └── customer_details.png              # Customer-level table preview screenshot
│
├── research/
│   └── Written_Report.pdf                # 3–5 Page Progress & Final Report
│
└── README.md                             # Project documentation homepage
