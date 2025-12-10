# 🚴‍♂️ AdventureWorks Analytics Dashboard — Power BI Project  
### **By: Mohammad Kaif Firoz**

An end-to-end Power BI dashboard analyzing sales, customers, products, and territory performance for the fictional company **AdventureWorks Cycles**.  
This project was built while learning Power BI through Maven Analytics and represents a complete business intelligence workflow—from raw data to interactive dashboards.

---

## 📂 Project Files Included

| File Name | Description |
|----------|-------------|
| **Adventure Works Report Dashboard KAIF FIROZ.pbix** | Full Power BI dashboard containing all visuals, DAX, and navigation |
| **AdventureWorks Raw Data/** | Folder containing all source datasets used in the report |
| **AdventureWorks Images/** | Screenshots used for visualization preview in documentation |
| **Sales Data (Integrated).csv** | Combined sales dataset |
| **AdventureWorks Calendar Lookup.csv** | Date dimension |
| **AdventureWorks Customer Lookup.csv** | Customer dimension |
| **AdventureWorks Product Lookup.csv** | Product dimension |
| **AdventureWorks Product Categories Lookup.csv** | Category dimension |
| **AdventureWorks Product Subcategories Lookup.csv** | Subcategory dimension |
| **AdventureWorks Returns Data.csv** | Returns dataset |
| **AdventureWorks Sales Data 2020.csv** | Sales (2020) |
| **AdventureWorks Sales Data 2021.csv** | Sales (2021) |
| **AdventureWorks Sales Data 2022.csv** | Sales (2022) |
| **AdventureWorks Territory Lookup.csv** | Territory dimension |
| **Product Category Sales (Unpivot Demo).csv** | Dataset used for unpivot demonstrations |

---

## 📌 1. Business Requirement

AdventureWorks leadership needed a **centralized reporting system** that provides:

- Company-wide KPIs (Revenue, Profit, Orders, Return %)
- Regional performance by **Continent → Country**
- Product-level insights (Categories, Subcategories, SKUs)
- Customer segmentation (Income level, Occupation, RFM-style metrics)
- AI-powered insights (Key Influencers & Decomposition Tree)
- Drill-through functionality for detailed product investigation

The goal: **Convert raw operational data into actionable insights** for business decision-making.

---

## 🎯 2. Analytical Goals

- Track overall business health through KPI monitoring  
- Compare regional performance across continents and countries  
- Identify high-performing and low-performing products  
- Evaluate customer behavior and revenue contribution  
- Highlight patterns using AI visuals (Key Influencers & Decomposition Tree)  
- Provide drill-through navigation for product-specific analytics  

---

## 🧹 3. Data Preparation & Modeling

Raw data was transformed using **Power Query** and modeled into a clean, analytical star schema.

### 🔧 Data Preparation Steps
- Cleaned and standardized column names  
- Created custom date table (rolling calendar)  
- Handled missing values  
- Unpivoted category-level sales for demo  
- Merged and appended sales tables  
- Added conditional, index, and time intelligence columns  
- Performed QA & profiling checks  

### 🏗️ Data Model Structure

**Fact Tables**
- Sales  
- Returns  

**Dimension Tables**
- Date  
- Customer  
- Product  
- Product Category  
- Product Subcategory  
- Territory  

Model includes:
- Proper primary & foreign keys  
- One-to-many relationships  
- Star schema optimization  
- Active & inactive relationships  
- DAX time intelligence support  

---

## 📊 4. Dashboard Pages & Visuals

### 🏠 Executive Dashboard  
KPIs, Revenue Trend, Top Products, Return Rate, Drill-through navigation.

---

### 🗺️ MAP Page  
- Sales by Continent  
- Bubble map for country-level detail  

---

### 📦 Product Detail Page  
- Dynamic metrics (Orders, Revenue, Profit, Returns)  
- Price Adjustment What-If parameter  
- Drill-through from main dashboard  
- Product trend analysis  

---

### 👥 Customer Detail Page  
- Top 100 customers  
- Revenue per Customer trend  
- Segmentation by income & occupation  
- Customer card visuals  
- Year slicers & dynamic metrics  

---

### 🌳 Decomposition Tree  
- Breaks down total orders → category → subcategory → product  
- Helps identify key drivers of performance  

---

### 🧠 Key Influencers (AI Visual)  
- Shows what influences **Average Retail Price**  
- Displays segments with highest probability of Home Ownership  
- Scatter trend lines for causal analysis  

---

## 🧠 5. Key Insights

- **United States** leads in revenue contribution  
- **Tires & Tubes** is the most ordered product type  
- **Shorts** category shows the highest return percentage  
- Revenue shows growth from 2020–2022 with seasonal patterns  
- Certain customer segments (higher income & professional roles) contribute significantly more revenue  
- Product cost strongly influences retail price (AI finding)  

---

## ⚙️ 6. Tools & Techniques Used

- Power BI Desktop  
- Power Query  
- DAX (40+ measures)  
- Time Intelligence  
- AI Visuals (Key Influencers, Decomposition Tree)  
- Drill-through Navigation  
- Bookmarks & Buttons  
- Data Modeling (Star Schema)  
- Performance Optimization  

---

## 🧮 7. Major DAX Measures Created

- Total Sales  
- Total Profit  
- Total Orders  
- Return %  
- Gross Margin  
- YoY Revenue  
- YoY Orders  
- Moving Averages  
- Top-N Filters  
- KPI measures for trending visualizations  

---

## 🧵 8. Interview Storytelling Summary

“I created an end-to-end Power BI dashboard for AdventureWorks that includes KPI summaries, customer analytics, product insights, and region-level sales data. The report uses a star schema, advanced DAX measures, AI visuals, and drill-through navigation. I transformed raw operational data into actionable insights, allowing decision-makers to understand performance across products, customers, and regions.”

---

## 📸 9. Dashboard Preview

### 🏠 Executive Dashboard  
[`Exce - Dasshboard Screenshot.png`](https://github.com/kaiffirox/AdventureWorks-Analytics-Dashboard-Power-BI-Project-/blob/main/Exce%20-%20Dasshboard%20Screenshot.png)
<img width="1552" height="869" alt="image" src="https://github.com/user-attachments/assets/2a2cf961-b071-4a8a-bcf2-121f1a9bfce1" />


### 🗺 MAP Page  
[`![Map Page](AdventureWorks Images/Map Page.png)`](https://github.com/kaiffirox/AdventureWorks-Analytics-Dashboard-Power-BI-Project-/blob/main/Map%20page%20Screenshot.png)
<img width="1544" height="866" alt="image" src="https://github.com/user-attachments/assets/e543b4fd-a74e-4c7b-8326-39b9fe060b91" />


### 📦 Product Detail Page  
[`![Product Detail](AdventureWorks Images/Product Detail.png)`](https://github.com/kaiffirox/AdventureWorks-Analytics-Dashboard-Power-BI-Project-/blob/main/Product%20details%20page%20Screenshot.png)
<img width="1541" height="865" alt="image" src="https://github.com/user-attachments/assets/0fc7253a-b041-460f-b6e0-5eafb3121d28" />



### 👥 Customer Detail Page  
[`![Customer Detail](AdventureWorks Images/Customer Detail.png)`](https://github.com/kaiffirox/AdventureWorks-Analytics-Dashboard-Power-BI-Project-/blob/main/Customer's%20details%20page%20Screenshot.png)
<img width="1548" height="870" alt="image" src="https://github.com/user-attachments/assets/e7a0d319-e394-4c86-b707-f079096cf86d" />



### 🌳 Decomposition Tree  
[`![Decomposition Tree](AdventureWorks Images/Decomposition Tree.png)`](https://github.com/kaiffirox/AdventureWorks-Analytics-Dashboard-Power-BI-Project-/blob/main/Decomposition%20Tree%20page%20Screenshot.png)
<img width="1536" height="865" alt="image" src="https://github.com/user-attachments/assets/1f5ddb0d-ec01-40b4-93ca-d26096c8707e" />


### 🧠 Key Influencers Page  
[`![Key Influencers](AdventureWorks Images/Key Influencers.png)`](https://github.com/kaiffirox/AdventureWorks-Analytics-Dashboard-Power-BI-Project-/blob/main/Key%20Unfluncers%20page%20Screenshot.png)
<img width="1550" height="864" alt="image" src="https://github.com/user-attachments/assets/86492e45-0f69-488b-922b-dec5511cb7d1" />



---

## 👨‍💻 10. Author

**Mohammad Kaif Firoz**  
Data Analyst — SQL | Power BI | Excel | Tableau | Python  

📧 Email: **kaifsidd2003@gmail.com**  
🔗 LinkedIn: **https://www.linkedin.com/in/kaiffiroz/**  

---

⭐ *If you found this project helpful, please consider starring the repository!* ⭐
