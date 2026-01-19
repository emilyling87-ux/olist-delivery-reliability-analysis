# Olist Delivery Reliability Analysis

🔗 **Dashboard (Looker Studio):** [View here]ttps://lookerstudio.google.com/reporting/c0ef3eb4-75c8-497a-9b7e-03b593a42f11

🧰 **Tools:** SQL (BigQuery), Looker Studio, Python, Excel  

📅 **Date:** Jan 2026

---

## Business Problem
Many Olist dashboards focus on sales and top products.  
This project focuses on **fulfillment reliability** and **SLA design**, asking:
- Does high SLA compliance mean deliveries are truly on time?
- What is hidden behind headline SLA metrics?
- How does delivery timing relate to customer satisfaction?

---

## Key Insight (Executive Summary)
**High SLA compliance can be misleading.**  
A large share of orders are delivered **systematically early**, inflating SLA compliance and masking poor true on-time performance.

---

## Key Findings
- Redefined delivery KPIs into **Early / Tight On-time (-2 to 0 days) / Late**
- Found early deliveries dominate the dataset and distort SLA interpretation
- Late deliveries are penalized strongly in customer reviews; early is not
- Seller-level patterns reveal structural reliability issues

---

## Dashboard Screenshots

### Overall Delivery Reality
![Overall Delivery Reality](overall_delivery.png)

### SLA Compliance vs True On-time
![SLA vs On-time](sla_masking.png)

### Delivery Timing vs Customer Satisfaction
![Customer Satisfaction](customer_satisfaction.png)

---

## Recommendations
- Redesign SLA KPI to separate **true punctuality** from **systematic earliness**
- Add operational thresholds for early delivery (cost/efficiency impact)
- Prioritize intervention on sellers with structurally high late rates

---

## Contact
- LinkedIn: www.linkedin.com/in/ling-li-data
