# 🧀 Power BI Dairy-Product-analysis-Dashboard
**📌 Objective:**<br>
To analyze dairy product performance using an interactive Power BI dashboard by exploring metrics like total value, revenue, customer reach, brand distribution, and storage conditions. This helps stakeholders monitor inventory levels, identify sales trends, and optimize distribution based on product lifecycle and storage modes.

**🧰 Tools Used:**<br>
1. Power BI – Dashboard development and data visualization
2. Power Query – Data transformation and cleaning and modeling
3. DAX – Custom calculations and KPIs

**📦 Dataset Overview:**<br>
| Column Name                   | Description                                            |
| ----------------------------- | ------------------------------------------------------ |
| `Location`                    | State or region where the dairy farm is located        |
| `Total Land Area (acres)`     | Size of the dairy farm in acres                        |
| `Number of Cows`              | Number of cows per farm                                |
| `Farm Size`                   | Categorized as Small, Medium, or Large                 |
| `Date`                        | Date of record                                         |
| `Product ID` / `Product Name` | Unique identifier and name of the dairy product        |
| `Brand`                       | Brand under which the product is sold                  |
| `Quantity (liters/kg)`        | Initial product quantity produced                      |
| `Price per Unit`              | Unit price of the product                              |
| `Total Value`                 | Total value based on produced quantity and unit price  |
| `Shelf Life (days)`           | Number of days the product remains sellable            |
| `Storage Condition`           | Required storage (e.g., Refrigerated, Frozen, Ambient) |
| `Quantity Sold (liters/kg)`   | Amount sold                                            |
| `Price per Unit (sold)`       | Selling price per unit                                 |
| `Approx. Total Revenue (INR)` | Revenue generated from sales                           |
| `Customer Location`           | Buyer location                                         |
| `Sales Channel`               | Online, Retail, or Wholesale                           |
| `Quantity in Stock`           | Remaining product in stock                             |
| `Minimum Stock Threshold`     | Minimum threshold before reorder is needed             |
| `Reorder Quantity`            | Suggested amount to reorder when stock is low          |



**📌 Key Metrics & KPIs:**<br>
1. Total Value: 118M
2. Total Revenue: 58.73M
3. Customer Locations: 15
4. Total Brands: 11
5. Storage Conditions: 5
6. Sales Modes: 3
7. Min Stock Threshold vs Available Stock
8. Revenue Trends by Month & Week

**📊 Visualizations:**<br>
1. 📅 Revenue by Month & Week
2. 🧑‍🌾 Value by Farm Size
3. 🧊 Value by Storage Condition
4. 📉 Quantity in Stock vs Minimum Stock Threshold

**📍 Slicer Panel for filtering by:**<br>
1. Date Range
2. Location
3. Farm Size
4. Brand
5. Storage Condition
6. Shelf Life
7. Sales Mode

**🔍 Recommended Analysis:**<br>
1. Monitor monthly and weekly revenue trends for seasonal planning
2. Identify top-performing storage conditions and optimize logistics
3. Compare performance across farm sizes to target supply partnerships
4. Use the stock threshold gauge to avoid inventory shortages
5. Track brand-level performance across multiple sales modes

**🔎 Key Insights:**<br>
1. The highest revenue month was January with over 5.9M
2. Refrigerated storage accounts for 58% of total value
3. Revenue is fairly consistent across the week, peaking on Sunday
4. There is a significant stock gap below the minimum threshold
5. Large farms contribute the most to overall product value

**📸 Dashboard Snapshot:** 
![Dashboard Snapshot](https://github.com/AyushMaurya19/Dairy-Product-analysis-Dashboard/blob/main/Snapshot%20of%20Dashboard.png)

