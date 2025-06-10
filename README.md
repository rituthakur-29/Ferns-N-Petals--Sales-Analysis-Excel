## 📝 Executive Summary: FNP Sales Analysis Dashboard

This project presents a comprehensive sales analysis for FNP (Ferns N Petals), leveraging Excel's advanced data tools, including Power Pivot, DAX measures, PivotTables, and slicers to create an interactive and insightful dashboard.

## 🔗 Dashboard Preview
![Image](https://github.com/user-attachments/assets/c524ec29-553b-48b6-b0cc-6032cf5b527e)

## 🧩 Data Model & Structure

This diagram represents the relationship between the three main tables imported into Excel:
- Customers
- Orders
- Products
  
![Image](https://github.com/user-attachments/assets/916270b3-1582-4e35-b412-a3d16ce58902)


## 🔧 Data Preparation:

- Cleaned and transformed raw data in Power Query Editor.
- Removed inconsistencies, standardized column formats, and created new calculated columns (like Revenue, Diff order delivery, etc.).
- Built proper one-to-many relationships for an efficient data model:
    - Customers[Customer_ID] → Orders[Customer_ID]
    - Products[Product_ID] → Orders[Product_ID]
- This structured data model enabled smooth creation of DAX measures and dashboard visualizations.

## 📊 Key Insights:

- Total Orders: 1,000
- Total Revenue Generated: ₹3,520,984
- Average Delivery Time: 5.53 days
- Customer’s Average Spend: ₹3,520.98

## 🔍 Deep-Dive Analyses:

- Top Performing Category: Colors contributed the highest revenue (₹1,005,645), followed by Soft Toys and Sweets.
- Revenue Trends by Time: Sales were relatively higher between 10 AM to 2 PM, suggesting peak order placement hours.
- Monthly Trends: February saw the highest revenue surge, likely linked to Valentine's Day.
- Occasion-Based Revenue: Anniversary and Raksha Bandhan drove the highest revenue, highlighting their commercial significance.
- Top Cities by Orders: Imphal, Dibrugarh, and Kavali showed the highest order volumes.
- Top Products by Revenue: Quia Gift and Deserunt Box were among the top-selling items.

## 🛠️ Tools & Techniques:
- Excel, Power Pivot, DAX Measures
- PivotTables, Charts, Slicers
- CORREL Function for statistical analysis
  
## 📈 Analytical Insight:
Order Quantity vs. Delivery Time:
Using Excel’s CORREL function, a correlation value of 0.0035 was observed, indicating a neutral/no significant relationship between order quantity and delivery time.

## 🧠 Project Reflection:
This is an inspired project in which I made several custom modifications, gaining hands-on experience in:
- Using Power Pivot to manage large datasets
- Creating custom DAX measures for insightful metrics
- Leveraging Excel's CORREL function to interpret relationships between variables
- Designing interactive dashboards using slicers and visuals

This project was a great learning experience, and I’m excited to apply these skills in more original, business-focused analytics projects soon.

## 👩‍💻 Author

**Ritu Thakur**  
🔗 [LinkedIn](https://linkedin.com/in/ritut)  
🛠️ Aspiring Data Analyst | Power BI | SQL | Excel | DAX

---
