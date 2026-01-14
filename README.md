# Logistics Shipment Performance Analysis

## Overview
This project analyzes shipping cost efficiency and delivery performance using real-world logistics shipment data. The goal is to identify cost patterns, carrier trade-offs, delivery reliability, and operational insights using data analytics, SQL, visualization, and basic machine learning.

This project is inspired by my experience as a **Logistics Coordinator**, where I managed small-parcel and LTL shipments, compared carrier rates, and maintained logistics data using SAP and Excel. I also collaborated with a colleague to analyze shipment data and build a Power BI dashboard that was presented in team meetings to support operational decision-making.

## Objectives
- Analyze shipping costs, transit time, and delivery performance across carriers
- Identify cost-efficiency patterns based on distance and shipment characteristics
- Compare carrier performance in terms of cost vs delivery speed
- Build an interactive Power BI dashboard for business insights
- Train a baseline machine learning model to predict on-time delivery risk

---

## Tools & Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **SQLite** (SQL-based analysis)
- **Power BI** (Interactive dashboard & reporting)
- **Machine Learning** (Logistic Regression – baseline model)
- **Jupyter Notebook**

---

## Key Analysis Performed

### Exploratory Data Analysis (EDA)
- Analyzed shipping cost distribution and outliers
- Compared shipping costs across carriers
- Examined cost vs distance and cost per mile trends
- Studied transit time patterns by distance range
- Evaluated delivery status distribution

---

### SQL Analysis (SQLite)
- Calculated average cost and cost per mile by carrier
- Identified most cost-efficient carriers
- Analyzed delivery performance and shipment volume
- Evaluated warehouse and distance-based cost trends

---

### Power BI Dashboard
I created a one-page interactive Power BI dashboard that includes:
- KPI cards for shipment volume, average cost, cost per mile, and delivery rate
- Carrier-level cost and transit time comparisons
- Delivery status distribution
- Distance-based efficiency and transit analysis
- Interactive slicers to filter by carrier, warehouse, month, and delivery status

---

### Machine Learning (Baseline Model)
- Built a **baseline logistic regression model** to predict whether a shipment will be delivered on time
- Used shipment distance, weight, cost, and carrier as features
- Evaluated model performance using accuracy and confusion matrix
- Achieved approximately **78% accuracy** on unseen test data

This model demonstrates how shipment characteristics can be used to assess delivery risk.

---

## Key Insights
- Shipping costs and transit times vary significantly by carrier
- Lower-cost carriers are not always the fastest or most reliable
- Cost per mile decreases as shipment distance increases, indicating economies of scale
- Transit time increases predictably with distance
- Shipment characteristics provide meaningful signals for predicting delivery delays

---

## Future Improvements
- Improve on-time labeling using SLA or promised delivery dates
- Add advanced models such as Random Forest or Gradient Boosting
- Incorporate seasonal and regional features
- Deploy the model for real-time delay risk prediction

---

## Author
**Hetav**  
Data Science Undergraduate | Logistics & Analytics Enthusiast
