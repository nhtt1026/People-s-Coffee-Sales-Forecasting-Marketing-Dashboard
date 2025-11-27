# Sales Forecasting & Marketing Dashboard for People’s Coffee

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

- **Overall performance – solid base with room to grow**  
  - Actual Sales 12M sit at **$1.46M**, with Forecast 12M at **$1.69M** – a **+15.41% Sales Variance %**.  
  - For a CBD office-heavy site, **+3.28% MoM Growth %** and **+10.31% QoQ Growth %** tell me the store is trending up, not just riding one good month.

- **Core coffees are mature, not shrinking heroes**  
  - Latte, Flat White and Cappuccino still dominate *Net Sales (Total)*, but they all carry **negative Variance %**:  
    - Latte **–10.68%**, Flat White **–6.88%**, Cappuccino **–9.39%**.  
  - Classic Melbourne pattern: volume is high, but growth has moved to food and alternates rather than more cups of the same coffee.

- **Food and breakfast are where the growth is**  
  - Fresh Sandwich: **+23.76% Variance %** – weekday lunch and grab-and-go are working.  
  - Cinnamon scroll: **+126.40% Variance %**, Berry Bircher: **+88.18% Variance %** – clear winners for morning trade.  
  - Bircher Muesli jumps from **$0 Actual Sales 12M** to **~$46.6K Forecast 12M**; that’s a strong signal that Melbourne CBD customers are leaning into “quick but healthy” breakfast.

- **Top 10 SKUs carry most of the upside**  
  - Top 10 Items with Highest Forecasted Sales:  
    - Actual Sales 12M **$831K** → Forecast 12M **$914K** (**+9.94% Variance %**).  
  - A small product set is responsible for almost all the expected uplift, which is typical for a tight city café menu.

- **Seasonality reflects office and holiday rhythms**  
  - Forecasted Sales by Month & Season show stronger months in **spring and autumn (Sept–Nov, Mar–May)** around **$130K–$155K**, when CBD office attendance and weather both help trade.  
  - **December–January** sit closer to **$100K–$120K**, matching Melbourne’s holiday exodus and quieter office periods.

---

## 7) Recommendations:

- **Defend the core coffee line while nudging baskets up**  
  - Keep Latte, Flat White and Cappuccino front and centre – they’re the default order for office workers.  
  - Use them as anchors: push “coffee + food” combos at breakfast and mid-morning to lift average ticket rather than chasing more cups alone.

- **Lean into food as the growth engine**  
  - Put **Cinnamon scroll, Berry Bircher, Fresh Sandwich and Bircher Muesli** on prime display and digital boards during commute and lunch windows.  
  - Treat them as hero items: limited-time flavours, bundle pricing with coffees, and clear signage for “fast grab” for office crowds.

- **Plan labour and ordering around Melbourne’s true peaks**  
  - Staff up and order aggressively for **spring and autumn** peaks; that’s when CBD foot traffic and outdoor-coffee culture align.  
  - In **Dec–Jan**, run leaner rosters, trim prep volumes, and shift focus to tourists and pass-through trade rather than full office capacity.

- **Use promotions surgically, not blanket discounts**  
  - Target low-forecast months and slower weeks with specific offers (e.g. afternoon pastry deals, rainy-day promos), instead of cutting prices across the board.  
  - Measure response in **MoM Growth %** and **Sales Variance %** for those months to keep only the campaigns that genuinely move the needle.

- **Continuously curate the Top 10 list**  
  - Review the **Top 10 Items with Highest Forecasted Sales** every quarter.  
  - Keep items with strong positive **Variance %** and solid margins; tweak recipe, price, or placement for those slipping, and don’t hesitate to retire chronic underperformers – Melbourne coffee drinkers are quick to adopt something better.
 
 ---
