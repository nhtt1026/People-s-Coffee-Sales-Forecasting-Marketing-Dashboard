## 1) Problem Overview:

People’s Coffee is a local café chain with three branches across Melbourne.  
This project focuses on the 440 Collins Street CBD branch, where management needs a data-driven way to:

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

**Main Dashboard Views**

1. **Sales Overview**
   - Total monthly revenue  
   - Number of monthly transactions  
   - Monthly sales trend  

2. **Forecast & Seasonality**
   - Historical vs forecasted monthly sales (next 12 months)  
   - Actual vs forecast variance  
   - Seasonality by month and year  

3. **Product Performance**
   - Top 10 and bottom 10 products by monthly revenue and quantity  
   - Monthly sales by product and category  
   - Products ranked by forecasted monthly demand  

4. **Demand & Low-Demand Periods**
   - Monthly demand trend across 36 months  
   - Identification of low-demand periods for potential campaigns  

---

## 5) Business Metrics:

- **Revenue & Volume**
  - Total sales revenue  
  - Number of transactions  
  - Units sold by product and category  

- **Forecast Metrics**
  - Forecasted monthly sales (12-month horizon)  
  - Actual vs forecast variance (value and %)  
  - Forecast accuracy for key products  

- **Product & Category Metrics**
  - Top / bottom products by sales  
  - Category contribution to total revenue  
  - Product mix over time  

- **Demand & Operations**
  - Demand patterns by month and year
  - Low-demand months for potential campaigns  
  - Inputs to monthly stock ordering and staff rostering 

---

## 6) Insights:

- **Overall performance**  
  - Actual Sales 12M: **$1.46M** vs Forecast 12M: **$1.69M** → **+15.41% Sales Variance %**  
  - Positive short-term momentum with **+3.28% MoM Growth %** and **+10.31% QoQ Growth %**.

- **Top products vs forecast**  
  - Latte, Flat White and Cappuccino remain the highest by Net Sales (Total), but all have **negative Variance %**  
    - Latte: –10.68%, Flat White: –6.88%, Cappuccino: –9.39%.

- **Emerging growth items**  
  - Fresh Sandwich: **+23.76% Variance %**.  
  - Cinnamon scroll: **+126.40% Variance %**.
  - Long Black: **+10.54% Variance %**.  
  - Berry Bircher: **+88.18% Variance %**.  

- **Top 10 portfolio impact**  
  - For the Top 10 Items with Highest Forecasted Sales, Actual Sales 12M total **$831K**, Forecast 12M **$914K** → **+9.94% Variance %** from just these 10 SKUs.

- **Seasonality**  
  - Stronger months in **spring and autumn (Sept–Nov, Mar–May)** around **$130K–$155K**.
  - Softer months in **Dec–Jan** closer to **$100K–$120K**.
  - Pattern aligns with CBD office rhythms and Melbourne holiday periods.

---

## 7) Recommendations:

- **Protect core coffee sales**  
  - Keep Latte, Flat White and Cappuccino front and centre, they’re the default order for office workers.  
  - Use them to lift basket size: push **coffee + pastry / breakfast** bundles during morning and mid-morning peaks to offset their negative Variance %.

- **Push high-growth food item**  
  - Prioritise **Cinnamon scroll, Berry Bircher, Fresh Sandwich** in display, menu boards and app tiles.
  - Actively promote them by:
    - Featuring them in “grab-and-go” offers for office workers.
    - Pairing them with core coffees at a small bundle discount.

- **Plan inventory and labour by season**
  - For **Sept–Nov, Mar–May** (**high forecast months, spring & autumn**), schedule more baristas and kitchen prep, order beans and ingredients in line with the forecast.
  - For **Dec–Jan** (**softer months**), run leaner rosters and tighter ordering, and test tourist-friendly or holiday-themed offers instead of staffing for full, as there's not much office traffic.
 
- **Use promotions surgically, not blanket discounts**  
  - Target low-forecast months with specific offers (e.g. rainy-day promos in Sep – Nov), instead of cutting prices across the board.  
  - Measure response in **MoM Growth %** and **Sales Variance %** for those months to keep only the campaigns that genuinely move the needle.
    
- **Continuously tune the product mix**
  - Review the **Top 10 Items with Highest Forecasted Sales** quarterly:
    - Keep items with strong positive **Variance %** and **good margins**.
    - Investigate declining core coffees (price perception, competition, quality drift).
    - Retire or reformulate items that sit in the bottom of the list with weak sales and no forecasted lift.
 
 ---
