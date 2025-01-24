#  Retail Store Analysis - PowerBI


Welcome to the **Retail-Store-Analysis** project! This project aims to analyze sales and performance data of a retail company, Blinkit grocery app which is an online store. This project leverages data provided by Data Tutorials(https://topmate.io/data_tutorials). The dataset, originally in Excel format, was imported into Power BI for data cleaning, transformation, and visualization.

---

## Project Overview
This project analyzes the sales and performance data of Blinkit, an online grocery store, using Power BI. The analysis aims to uncover insights into sales trends, customer satisfaction, inventory distribution, and business optimization opportunities.

### Key Deliverables
- Interactive Power BI dashboards.
- Insights into sales performance across various dimensions (e.g., outlet type, item fat content, geographic distribution).
- Actionable recommendations based on the analysis.

---

## Data Description
- **Data Source:** Excel file containing sales, outlet, and product data.
- **Key Fields:**
  - **Item Information:** Item identifier, item type, item fat content, item weight.
  - **Outlet Information:** Outlet establishment year, outlet location type (tier 1, tier 2, tier 3), outlet size (small, medium, large), outlet type (e.g., supermarket tier1, supermarket tier2, grocery store).
  - **Performance Metrics:** Total sales, product rating by customers.

---

## Key Performance Indicators (KPIs)
- **Total Sales:** Overall revenue from all items sold. $1.2 million in overall revenue.
- **Average Sales:** Average revenue generated per sale.
- **Number of Items Sold:** Count of different items sold. 1232 (fruits and snacks being the top category).
- **Customer Rating:** Average rating for sold items. 

---

## Business Requirements
1. **Impact of Fat Content on Sales:**
   - Analyze the sales contribution from low-fat vs. high-fat items.
2. **Influence of Establishment Age on Sales:**
   - Evaluate how the year of establishment correlates with sales performance.
3. **Outlet Size Analysis:**
   - Determine the contribution of outlet size to total sales.
4. **Geographic Sales Distribution:**
   - Assess sales performance across different location tiers.

---


## Visual Insights

### 1. Donut Chart: Total Sales by Fat Content
- **Insight:** 
  - **Low-fat items** account for 65% of total sales.
  - **High-fat items** account for 35% of total sales.
 
<img src="https://github.com/user-attachments/assets/e531fa12-8f99-4ad9-bb52-11abab7bdb99"   width="230" 
     height="220" />
- **Recommendation:** Focus on promoting low-fat items as they drive the majority of sales.

### 2. Clustered Bar Chart: Sales by Outlet Type and Tier
- **Insight:**
  - **Tier 3 outlets** generate the most sales and revenue (40%, $472k).
  - Most sales in tier 3 outlets are from medium-sized supermarkets selling low-fat items.
  
<img src="https://github.com/user-attachments/assets/4713e9ec-4a89-4b67-a188-48657645d1f5"   width="250" 
     height="200" />
- **Recommendation:** Expand tier 3 outlets, especially medium-sized supermarket type 3, to capitalize on this trend.

### 3. Stacked Bar Chart: Sales by Item Type
- **Insight:**
  - **Fruits and snacks** generate the highest revenue ($175k) and sell the most items (1232).
  - **Seafood** generates the least revenue ($9k) and has the lowest items sold (64).

<img src="https://github.com/user-attachments/assets/c62a3ba6-c8ae-481f-bfa4-e083c6e5de4c"   width="230" 
     height="320" />
- **Recommendation:** Increase inventory and promotions for high-demand items like fruits and snacks, and consider reevaluating the strategy for seafood.

### 4. Line Chart: Sales by Outlet Establishment Year
- **Insight:**
  - Stores established between 2011 and 2017 show average sales of $130k.
  - Stores established in 2018 perform exceptionally well, with sales of $205k.

<img src="https://github.com/user-attachments/assets/6667fcfc-608f-4638-b621-4f17d5ed3006"   width="450" 
     height="280" />
- **Recommendation:** Investigate best practices from stores established in 2018 and replicate their strategies in older stores.

### 5. Sales Distribution by Outlet Size
- **Insight:**
  - Medium-sized outlets contribute 42% of total sales.
  - Large-sized outlets account for only 20% of total sales.
- **Recommendation:** Focus on optimizing and expanding medium-sized outlets for better sales performance.

### 6. Geographic Distribution of Sales
- **Insight:**
  - Tier 3 outlets dominate with 40% of total sales, amounting to $472k.
- **Recommendation:** Strengthen supply chain and inventory management in tier 3 locations to meet demand efficiently.


---

## Visualizations
- **Donut Chart:** Total sales by fat content.
- **Clustered Bar Chart:** Sales by outlet type and tier.
- **Stacked Bar Chart:** Sales by item type.
- **Line Chart:** Sales by outlet establishment year.
- **Geographic Map:** Sales distribution by outlet location type.
- 
![image](https://github.com/user-attachments/assets/69494afc-2f45-401c-b530-6540fe4afcdc)


---

## Insights and Recommendations
- **Focus on low-fat items** for promotions and inventory allocation.
- **Expand operations in tier 3 locations**, especially medium-sized supermarket type 3 outlets.
- **Promote high-performing items like fruits and snacks**, while reevaluating strategies for low-performing categories like seafood.
- **Replicate successful strategies** from stores established in 2018 to improve the performance of older stores.
- **Optimize medium-sized outlets** as they contribute significantly to total sales.

---

## Tools and Technologies
- **Tools Used:**
  - Microsoft Power BI for visualization and analysis.
  - Excel for data preparation and initial exploration.
- **Technologies:**
  - DAX for creating calculated measures and KPIs.
  - Power Query for data cleaning and transformation.

---

## Implementation Plan
1. **Data Cleaning and Preparation:**
   - Import dataset from Excel into Power BI and cleaning.
2. **Data Transforming:**
   - Ensuring datatypes are correct and handling inconsistencies.create aggregates Total sales, No of Items, Avg Rating, Avg sales.
3. **Visualization Development:**
   - Build the required dashboards and charts in Power BI.
4. **Insights Extraction:**
   - Analyze the visuals and prepare actionable insights.
5. **Delivery:**
   - Share the final dashboards and summary reports with stakeholders.

---



Feel free to copy and paste this into your GitHub repository's README file. Let me know if further customization is required!
