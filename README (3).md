# Diagnostic-Analysis
# *Diagnostic Analysis of Adidas US Sales Performance*  

## *Project Description*  
This project conducts a *diagnostic analysis* to investigate the underlying causes of sales fluctuations in Adidas US retail data (2020-2021). By leveraging sales transactions, retailer performance, product categories, and regional trends, we identify key factors influencing sales performance and provide actionable recommendations for improvement.  

---  

## *📌 Project Title*  
*Investigating Sales Trends & Performance Drivers in Adidas US Retail (2020-2021)*  

---  

## *🎯 Objective*  
The primary goal is to:  
✔ Identify key drivers of sales performance  
✔ Analyze correlations between sales, pricing, and operational metrics  
✔ Segment customers and products to uncover high-value opportunities  
✔ Provide data-backed recommendations for strategic improvements  

---  

## *📊 Dataset Overview*  
The dataset includes *Adidas US sales transactions (2020-2021)* with the following key features:  

| *Column*          | *Description*                          |
|---------------------|------------------------------------------|
| Retailer          | Retailer name like, Foot Locker |
| Retailer ID       | Unique identifier for each retailer      |
| Invoice Date      | Date of transaction         |
| Region           | Geographic sales region (East, West, etc.) |
| State & City   | Location of sale                        |
| Product          | Product category (e.g., Men’s Apparel, Women’s Athletic Footwear) |
| Price per Unit   | Selling price per item                  |
| Units Sold       | Quantity of items sold                  |
| Total Sales      | Revenue generated per transaction       |
| Operating Profit | Profit after costs                      |
| Operating Margin | Profitability percentage                |
| Sales Method     | Online, In-Store, or Outlet            |

---  

## *🔍 Methodology*  

### *1. Data Collection & Preparation*  
- Cleaned and normalized sales data  
- Handled missing values and outliers  
- Engineered time-based features (Month, Quarter, Year)  

### *2. Trend Analysis*  
📉 *Key Insight:* Sales peaked in Q4 (holiday season) but declined in early 2021.  
📊 *Product Performance:*  
- *Top-performing:* Men’s Street Footwear ($96M)  
- *Underperforming:* Women’s Apparel ($72M)  

### *3. Correlation Analysis*  
📌 *Strongest Correlations with Sales:*  
✔ *Positive:* Units Sold (0.92), Operating Profit (0.85)  
❌ *Negative:* Price per Unit (-0.45) → Higher pricing may deter volume sales  

### *4. Root Cause Analysis (Simulated Survey Data)*  
🔎 *Top Customer Complaints:*  
1. *Pricing (45%)* – Customers perceive high prices  
2. *Stock Availability (38%)* – Frequent out-of-stock issues  
3. *Customer Service (28%)* – Negative shopping experiences  

### *5. Segmentation Analysis*  
👥 *Customer Segments:*  
| *Segment*       | *Behavior*                          | *Revenue Contribution* |
|-------------------|---------------------------------------|--------------------------|
| *High-Value*    | Frequent buyers, high spending        | 58% of total sales       |
| *Medium-Value*  | Occasional purchases, moderate spend  | 30% of total sales       |
| *Low-Value*     | Rare purchases, low spend             | 12% of total sales       |

📦 *Product Performance by Segment:*  
- *High-Value Buyers:* Prefer *Men’s Street Footwear* ($83.7M)  
- *Medium-Value Buyers:* Favor *Women’s Athletic Footwear* ($53.6M)  

---  

## *🚀 Key Findings & Recommendations*  

### *🔎 Findings:*  
1. *Sales Decline Factors:*  
   - *Pricing sensitivity* (higher prices reduce volume)  
   - *Stockouts* in popular categories (lost sales)  
   - *Regional disparities* (West underperforms vs. East)  

2. *Growth Opportunities:*  
   - *Men’s Street Footwear* is the highest revenue driver  
   - *High-value customers* contribute *58% of sales*  

### *📢 Recommendations:*  
✅ *Adjust Pricing Strategy:*  
   - Test dynamic pricing for high-demand products  
   - Offer bundle deals to increase average order value  

✅ *Improve Inventory Management:*  
   - Reduce stockouts in *Women’s Athletic Footwear*  
   - Optimize regional distribution based on demand  

✅ *Enhance Customer Retention:*  
   - Launch loyalty programs for *high-value segments*  
   - Improve customer service based on feedback  

---  

## *🛠 Technologies Used*  
- *Python* (Pandas, NumPy, Matplotlib, Seaborn)  
- *Jupyter Notebook* (Analysis & Visualization)  
- *Statistical Methods* (Correlation, RFM Segmentation)  
