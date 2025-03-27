# data-analyst-ravneet
# *Surviving the Titanic: Exploratory Data Analysis*  

## *📌 Project Overview*  
This project performs an *Exploratory Data Analysis (EDA)* on the *Titanic dataset* to uncover factors influencing passenger survival. Using Python (Pandas, Matplotlib, Seaborn), we analyze key features like *age, gender, class, and fare* to identify survival trends.  

---

## *🔍 Methodology*  

### *1. Data Collection & Preparation*  
- Loaded and cleaned the dataset (handled missing values, dropped irrelevant columns).  
- Converted data types for better analysis like, categorical encoding.  

### *2. Descriptive Statistics*  
- Analyzed numerical features (Age, Fare) and categorical distributions (Pclass, Sex).  
- Calculated survival rates across different groups.  

### *3. Data Visualization*  
- *Histograms & Boxplots*: Examined distributions of Age and Fare.  
- *Bar Charts*: Compared survival rates by gender, class, and age groups.  
- *Heatmaps*: Visualized correlations between numerical variables.  

### *4. Survival Analysis*  
- Gender: Women had a *74% survival rate* vs. *19% for men* (p < 0.0001).  
- Class: *1st-class passengers* had the highest survival rate (~63%).  
- Age: *Children (<12)* had better survival chances, especially in higher classes.  

---

## *💡 Key Insights & Findings*  
✔ *"Women and children first" policy was evident* – females and young passengers had significantly higher survival rates.  
✔ *Class disparity* – 1st-class passengers had *3x higher survival* than 3rd-class.  
✔ *Age mattered* – Children in 1st/2nd class were prioritized, while elderly passengers struggled.  

---

## *🎯 Conclusion & Next Steps*  
The analysis confirms *socioeconomic and demographic biases* in Titanic survival. Further steps could include:  
- *Predictive modeling* (Logistic Regression, Random Forest) to classify survival.  
- *Feature engineering* (family size = SibSp + Parch) for deeper insights.  
- *Hypothesis testing* to validate observed trends statistically.  

---

## *🛠 Technologies Used*  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Google Colab

- # Descriptive-Analysis
# Understanding Shopping Patterns in Istanbul Malls (2021-2023)

## Project Description
This project analyzes customer purchase data from 10 major shopping malls in Istanbul between 2021-2023 to identify key shopping trends and behaviors.

## Objective
To uncover actionable insights about:
- Seasonal shopping patterns
- Product category preferences
- Payment method trends
- Customer segmentation
- Mall performance comparisons

## Dataset
The dataset contains 994,482 transactions with:
- Invoice details (number, date, time)
- Customer demographics (age, gender)
- Purchase information (category, quantity, price)
- Payment methods (cash, credit, debit)
- Mall locations

## Key Findings
1. *Peak Shopping*: July 2021 saw highest sales (likely due to post-pandemic recovery)
2. *Top Category*: Clothing dominated with 114M TL in sales
3. *Payment*: Cash preferred (44.7%) over cards
4. *Segments*: 
   - New Customers (45,402)
   - Hibernating (44,997) 
   - Potential Loyalists (6,563)

## Recommendations
1. *Inventory Planning*: Boost clothing stock before summer season
2. *Promotions*: Target cash users with loyalty programs
3. *Staffing*: Increase weekend workforce
4. *Marketing*: Reactivate hibernating customers
5. *Mall Strategies*: Customize offerings based on time patterns

## Methodology
1. *Data Preparation*: Cleaned 994K+ records, handled missing values
2. *Analysis*: Calculated RFM metrics, time trends, category distributions
3. *Visualization*: Created interactive dashboards of key metrics
4. *Segmentation*: Identified 6 distinct customer groups

## Technologies Used
- Python (Pandas, Seaborn, Matplotlib)
- RFM analysis

- # Diagnostic-Analysis
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

# Data-Wrangling
# Data Wrangling for Enhanced Customer Analytics at EcoBloom

## Project Description

This project focuses on performing comprehensive data wrangling for customer analytics at EcoBloom, a sustainable home goods retailer. The goal is to clean, transform, and consolidate data from various sources to create a robust dataset for analysis. This will enable better decision-making and targeted marketing strategies.

## Datasets

The project uses the following datasets:

* **sales.csv:** Contains sales transaction records, including customer IDs, purchase amounts, product details, and timestamps.
* **customers.csv:** Contains customer demographic details such as age, gender, location, and account creation date.
* **service.csv:** Contains customer service records, including inquiry types, resolutions, and timestamps.
* **marketing.csv:** Contains marketing interaction data, including campaign names, email open rates, click-through rates, and timestamps.

## Methodology

1.  **Data Collection:**
    * Gathered Ecobloom datasets from CSV files.
2.  **Data Assessment:**
    * Conducted an initial assessment of data quality to identify missing values, duplicates, and inconsistencies.
    * Documented data types, formats, and discrepancies.
3.  **Data Cleaning:**
    * Addressed missing values through imputation.
    * Removed duplicate records.
    * Standardized date formats.
4.  **Data Transformation:**
    * Performed data type conversions.
    * Derived new features like, `purchase_month`, `customer_tenure`.
    * Aggregated data like, monthly sales.
5.  **Data Consolidation:**
    * Merged datasets into a unified customer database using `customer_id` as the key.
6.  **Documentation and Validation:**
    * Documented the data wrangling process.
    * Validated the final dataset through exploratory data analysis (EDA).
![image](https://github.com/user-attachments/assets/926955a3-af5e-496c-b01c-fb8574c74fc7)

## Tools and Technologies

* **Python:**
    * Pandas: For data manipulation and cleaning.
    * NumPy: For numerical operations.
    * Matplotlib: For data visualization.
    * Seaborn: For enhanced data visualization.



- # Data-Quality-Control
# eBay Car Sales Data Quality Control Project

## Project Description

This repository contains the implementation of a comprehensive Data Quality Control (DQC) framework for the eBay Car Sales Dataset. The project follows the Data Quality Control Initiative to ensure the accuracy, completeness, consistency, and reliability of the organization's data.

## Dataset Information

The dataset contains vehicle listings from eBay with the following key attributes:
- Vehicle details (name, brand, model, type)
- Pricing information
- Technical specifications (year of registration, gearbox type, power, mileage)
- Seller information
- Listing dates and status

## Methodology

- *Data Assessment*: Initial analysis of dataset structure and quality
- *Data Profiling*: Statistical summaries and distribution visualizations
- *Data Cleaning*: Standardization, outlier removal, and missing value treatment
- *Data Validation*: Automated checks using Great Expectations
- *Quality Metrics*: Calculation of completeness, validity, uniqueness, and consistency scores
- *Monitoring Dashboard*: Visualizations of key quality indicators
![image](https://github.com/user-attachments/assets/42ae23df-b67b-422c-a687-ccfd28625666)

## Tools

- Python 
- pandas
- numpy
- matplotlib
- seaborn
- great-expectations

- ![AWS_Academy_Graduate___AWS_Academy_Cloud_Foundations_Badge20250327-24-615t49_page-0001](https://github.com/user-attachments/assets/0c4df90a-e727-4a7c-9e8d-67dbbccfdbd2)





