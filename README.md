## 1) Problem Overview:

[People’s Coffee](https://peoplescoffee.com.au/) is a local café chain with 3 branches across Melbourne.

This project is inspired by the 440 Collins Street CBD branch and uses simulated POS data to answer a real-world business question. The branch manager needs a data-driven way to:

- Track sales performance over time  
- Forecast future demand  
- Identify low-demand periods  
- Optimise staffing and stock levels

The goal is to turn raw POS data into clear metrics and visuals that support daily operational and marketing decisions.

---

## 2) Introduction:

- Dataset: 36 months of historical POS sales data from the 440 Collins Street branch  
- Scope: Single-branch analysis and 12-month sales forecast  
- Tools:
  - **Power BI** for data modelling and interactive dashboards  
  - **Forecasting tool** (e.g. SAS EM) for time-series models  
  - **Excel/CSV** for initial data preparation  

---

## 3) Steps Have Been Done:

1. Collected 36 months of POS transaction data  
2. Cleaned and pre-processed the data:
   - Removed duplicates and handled missing values  
   - Tagged seasonal patterns (month, year, holidays and special periods)  
3. Built time-series forecasting models for total branch sales and key products
4. Modelled data in Power BI (fact & dimension tables)  
5. Created interactive dashboards for:
   - Monthly sales trends  
   - Forecast vs actual  
   - Product performance  
   - Low-demand months
6. Reviewed outputs with stakeholders and documented usage & assumptions  

---

## 4) Dashboard:

<img width="2398" height="1324" alt="image" src="https://github.com/user-attachments/assets/1a2b5da5-2b62-4921-8562-6238ed8ea88f" />

---

## 5) Business Metrics:

- **Sales & Growth:** Actual Sales 12M, monthly Net Sales, MoM % and QoQ %  
- **Forecast:** Forecast Sales 12M, Sales Variance (%), Net Sales Trend (Actual vs Forecast)  
- **Products & Categories:** Net Sales by item & category, Top 10 Best-Selling Items, Top 10 Items with Highest Forecasted Sales  
- **Seasonality & Demand:** Forecasted Sales by Month & Season, Holiday vs Non-Holiday performance

---

## 6) Insights:

- **Sales & Growth:**
  - Actual Sales 12M: $1.46M vs Forecast 12M: $1.69M → +15.41% Sales Variance %
  - Positive short-term momentum with +3.28% MoM and +10.31% QoQ growth.

- **Core Coffee Range:**
  - Latte, Flat White, Cappuccino are top items by Net Sales (Total) but each shows negative Variance % (–10.68%, –6.88%, –9.39%), indicating mature but flattening products.

- **Food & Breakfast Items:**
  - Fresh Sandwich (+23.76% Variance %), Cinnamon scroll (+126.40%), Berry Bircher (+88.18%) and Bircher Muesli ($0 → ~$46.6K) are key growth drivers in the Top 10 forecasted items.

- **Top 10 Items Impact:**
  - Top 10 Items with Highest Forecasted Sales: Actual 12M $831K → Forecast 12M $914K (+9.94%), showing a small SKU set drives most projected uplift.

- **Seasonality:**
  - Spring and autumn months (Sept–Nov, Mar–May) forecast ~$130K–$155K; Dec–Jan sits closer to $100K–$120K, matching CBD office and holiday patterns.

---

## 7) Recommendations:

### Sales & Growth:
- Protect the current $1.46M run-rate while aiming to realise the $1.69M forecast; focus on improving mix and basket size rather than heavy discounting.
- Use MoM Growth % and QoQ Growth % as early-warning metrics. If either turns negative for 2 months in a row, review pricing, service speed and local competition.

### Core Coffee Range:
- Keep Latte, Flat White and Cappuccino as flagship drinks on the menu, but treat them as stable base volume rather than growth drivers.
- Build “coffee + food” bundles around these core coffees to lift average ticket value and offset their negative Variance %.
- Monitor Variance % for these items after bundle and loyalty campaigns to confirm whether performance is stabilising or still slipping.

### Food & Breakfast Items:
- Feature Fresh Sandwich, Cinnamon scroll, and Berry Bircher prominently in cabinets and app orders during breakfast and lunch; they are the main growth drivers.
- Create targeted bundles to convert coffee-only visits into higher-value orders. For example:
  - Morning treat: Latte + Cinnamon scroll
  - Healthy breakfast: core coffee (e.g. Flat White or Long Black) + Berry Bircher or Bircher Muesli
  - Lunch: Fresh Sandwich + any core coffee
- Track Bircher Muesli’s actual sales against its ~$46.6K forecast over the next few months to decide whether to expand the line or adjust recipe/pricing.

### Top 10 Items Impact:
- Prioritise stock levels, staff training and promo placement for the Top 10 Items with Highest Forecasted Sales, as they generate most of the projected +9.94% uplift.
- Review each Top 10 item quarterly: keep investing in SKUs with strong + Variance % and good margins. Rework or retire items that stay flat or negative.

### Seasonality:
- Plan rosters and ordering around spring and autumn (Sept–Nov, Mar–May) as peak months at ~$130K–$155K; ensure enough baristas, kitchen prep and inventory.
- Run leaner rosters and tighter ordering in Dec–Jan (~$100K–$120K) and use targeted campaigns (tourist/holiday offers) instead of broad discounts.
- Use the Month, Season and Holiday filters to test seasonal drinks and promotions, keeping only those that visibly improve MoM Growth % for that period.
 
 ---
