# Sales Forecasting & Marketing Dashboard for People’s Coffee

## 1) Problem Overview

People’s Coffee is a locally owned café chain with three branches across Melbourne. This project focuses on the 440 Collins Street branch in Melbourne CBD, where the main customers are busy office workers who expect fast service and consistently good coffee.

Although the café is already performing well, it lacks a data-driven way to:

- Anticipate future sales and demand  
- Identify low-demand periods  
- Plan staffing and inventory efficiently  
- Target promotions at the right time with the right products  

Without proper forecasting and analytics, the café risks overstaffing/understaffing, stock issues, and missed opportunities to grow revenue during quieter periods.

---

## 2) Introduction

This project delivers a **Sales Forecasting & Marketing Dashboard** for People’s Coffee at the 440 Collins Street branch.

### Scope & Objectives

- Use **36 months of historical POS sales data** from the Collins Street branch  
- Build **time-series forecasting models** to predict monthly sales for the next 12 months  
- Design an **interactive Power BI dashboard** that combines:
  - Historical performance  
  - Forecasted sales  
  - Product-level insights  
  - Seasonality and low-demand periods  
- Support business decisions related to:
  - Stock ordering and bean purchasing  
  - Staff rostering  
  - Targeted promotions and menu optimisation  

The solution is scoped to the Collins Street branch; multi-branch rollout and real-time POS integration are considered future enhancements.

### Tools & Technologies

- **Power BI** – Data modelling, visualisation, and interactive dashboards  
- **Statistical forecasting tool (e.g. SAS / similar)** – Time-series forecasting and accuracy evaluation  
- **Excel / CSV** – Data preparation and validation  

---

## 3) Steps Have Been Done

1. **Requirements & Project Planning**
   - Gathered requirements from the café owner and manager:
     - How to forecast monthly sales reliably  
     - When low-demand periods occur  
     - Which products are top and under-performers  
   - Defined success criteria:
     - Reasonable forecast accuracy for high-volume items  
     - Clear visibility of seasonal patterns and low-demand periods  

2. **Data Collection & Cleaning**
   - Collected **36 months of POS transaction data** for the Collins Street branch  
   - Checked data completeness, corrected errors, removed duplicates  
   - Created flags for events/holidays to better capture demand drivers  

3. **Feature Engineering & Data Preparation**
   - Aggregated raw transactions into **daily and monthly** time series  
   - Built product-level metrics:
     - Quantity sold  
     - Revenue  
   - Prepared final fact and dimension tables for forecasting and Power BI

4. **Forecast Model Development**
   - Built **time-series forecasting models** to predict monthly sales for the next 12 months  
   - Focused on total branch sales and key high-volume items  
   - Evaluated models against historical data using standard error/accuracy metrics  

5. **Power BI Dashboard Design & Development**
   - Modelled data in Power BI using a star schema  
   - Designed multiple report pages including:
     - Sales overview and key KPIs  
     - Forecast vs actual views  
     - Product performance (top and bottom items)  
     - Seasonality and low-demand patterns (e.g. heatmaps, trend charts)  

6. **Validation, Testing & Handover**
   - Reviewed dashboard and forecasts with stakeholders  
   - Validated that visuals were understandable and performed well  
   - Documented methodology, assumptions, and usage instructions  
   - Conducted a walkthrough so the café team can use the dashboard operationally  

---

## 4) Dashboard
<img width="2410" height="1354" alt="image" src="https://github.com/user-attachments/assets/5f3de82c-6622-4baa-8d22-a16e9c73d7fe" />

### Dashboard Views

1. **Sales Overview**
   - Total revenue and transaction count  
   - Historical sales trend (monthly)  
   - High-level KPIs for the Collins Street branch  

2. **Forecast & Seasonality**
   - Line chart with **historical vs forecasted monthly sales**  
   - Clear distinction between actual and forecast periods  
   - Visibility of seasonality and key months  

3. **Product Performance**
   - **Top 10 and Bottom 10 products** by sales and quantity  
   - Products ranked by forecasted demand for the next 12 months  
   - Filters to focus on least forecasted products (underperformers)  

4. **Demand Heatmap & Low-Demand Periods**
   - Heatmap by month/day to highlight patterns in demand  
   - Identification of low-demand periods that can be targeted with campaigns
     
---

## 5) Business Metrics

The dashboard tracks a set of business metrics that support better decision-making for People’s Coffee:

1. **Revenue & Volume**
   - Total sales revenue  
   - Number of transactions/orders  
   - Units sold by product and product category  

2. **Forecasting Metrics**
   - Forecasted monthly sales for the next 12 months  
   - Forecast vs actual variance (absolute and percentage)  
   - Accuracy of forecasts for high-volume items  

3. **Product & Category Performance**
   - Sales by product and category (e.g. coffee, food, merchandise)  
   - Top 10 and bottom 10 products by revenue and quantity  
   - Products projected to drive future sales  

4. **Seasonality & Demand Patterns**
   - Month-on-month sales trends  
   - Comparison of normal days vs holidays/events  
   - Identification of low-demand periods across the year  

5. **Operational Metrics**
   - Indicators to assist **stock ordering** based on forecast demand  
   - Demand peaks and troughs to support **staff rostering**  

---

## 6) Insights

Key insights from the analysis and forecasting:

- **Seasonal Demand Patterns**  
  Sales show clear seasonal behaviour, with certain months and periods consistently performing higher than others. Recognising these patterns allows the café to prepare stock and staffing ahead of time.

- **High Dependence on a Core Set of Products**  
  A small group of high-performing items accounts for a large share of total revenue. These products are critical to maintain quality and availability and are strong candidates for promotional focus and upsell strategies.

- **Persistent Low-Demand Periods**  
  The dashboard reveals time windows and days that are structurally quieter. These low-demand periods represent opportunities for targeted promotions, special offers, or operational changes rather than relying on guesswork.

- **Better Visibility for Stock & Bean Ordering**  
  Forecasts at monthly and product levels support more precise ordering, improving stock availability while reducing waste and overstock.

- **Data-Driven Rostering**  
  By using forecasted peaks and troughs, staff schedules can be aligned more closely with expected customer flow, improving service while managing labour costs.

Overall, the café can move from **reactive** decisions based on intuition to **proactive** planning grounded in data and forecasts.

---

## 7) Recommendations

Based on the dashboard and forecasting results, the following actions are recommended:

1. **Run Targeted Promotions in Low-Demand Periods**
   - Use the demand heatmap and trend visuals to identify consistently quiet days and times  
   - Design targeted campaigns (discounts, bundles, loyalty offers) for these specific windows  
   - Monitor the uplift in sales after promotions and iterate on the most effective tactics  

2. **Prioritise High-Performing and High-Forecast Products**
   - Highlight top-selling items in menus, signage, and marketing materials  
   - Consider bundles or cross-selling strategies that feature these key products  
   - Ensure supply chain and ordering processes protect availability of these items  

3. **Review & Optimise Underperforming Products**
   - Evaluate bottom 10 products in terms of demand and profit margin  
   - Consider recipe changes, repositioning, or removal from the menu if they remain consistently weak  
   - Use the dashboard to track changes after any menu adjustments  

4. **Align Stock Ordering with Forecast Demand**
   - Use monthly and product-level forecasts as the basis for bean and ingredient ordering  
   - Reduce over-ordering on products with declining forecasted demand  
   - Track actual vs forecast over time to refine ordering assumptions  

5. **Use Forecasts as an Input to Staff Rostering**
   - Align peak shifts with forecasted high-demand periods (e.g. certain months or event days)  
   - Reduce staffing during consistently low-demand periods while maintaining core service levels  
   - Incorporate the dashboard into regular planning meetings  

6. **Maintain Data Quality and Refresh the Dashboard Regularly**
   - Ensure POS exports are complete and consistent each month  
   - Refresh the Power BI report on a regular cadence so decisions are always based on recent data  
   - Collect feedback from store managers and staff to evolve the dashboard as needs change  

---

This project demonstrates how combining **time-series forecasting** with an **operational Power BI dashboard** can help a single café branch manage sales, staffing, stock, and marketing in a more informed and proactive way, and provides a foundation for scaling analytics to additional locations in the future.
