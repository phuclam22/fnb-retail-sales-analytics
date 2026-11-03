# F&B Retail Sales & Loyalty Program Analytics

## Project Overview
In the highly competitive F&B retail sector, understanding customer purchasing habits, product preferences, and the effectiveness of retention strategies is vital. This project transforms fragmented transactional records across multiple operational tables (Orders, Customers, Products) into a unified, interactive **Excel Dashboard**. 

The core objective is to extract actionable insights regarding packaging size preferences, product types, and the commercial impact of the customer loyalty program to support data-driven procurement and marketing decisions.

## Tech Stack & Analytical Techniques
* **Data Integration:** Bypassed basic VLOOKUPs by engineering dynamic 2-way lookups utilizing **INDEX/MATCH** and modern **XLOOKUP** functions nested with `IF` logic. This successfully merged relational tables (Customer CRM data and Product metadata) into a robust master dataset.
* **Data Cleansing & Formatting:** Applied Custom Number Formatting (e.g., configuring packaging sizes to automatically display as "kg" and standardizing currency to USD) to ensure executive-ready reporting.
* **Interactive Data Visualization:** Architected a dynamic dashboard featuring standard PivotTables and PivotCharts (Line, Bar). Integrated an interactive **Timeline** and synchronized **Slicers** (Packaging Size, Roast Type, Loyalty Card Status) via Report Connections, enabling cross-dimensional data filtering.

## 📸 Dashboard Preview
<img width="937" height="538" alt="Screenshot 2026-11-04 013341" src="https://github.com/user-attachments/assets/25c9d688-e52d-46db-a254-949c9fa209f5" />


## Key Business Insights
Based on the analysis of **$45,134.25** in total revenue:

1. **Bulk Packaging Dominance:** The 2.5kg packaging size absolutely dominated sales, generating **$23,785.57** (over 52% of total revenue). This indicates a strong customer preference for bulk purchasing over trial sizes, as the 0.2kg package only yielded $3,307.95.
2. **Loyalty Program Gap:** Customers *without* a loyalty card generated higher revenue (**$24,216.41**) compared to loyalty members ($20,917.85). This reveals a massive untapped potential to convert high-spending walk-in customers into loyal members.
3. **Product Preferences:** Excelsa coffee ($12,306.44) and the Light roast type ($17,354.47) emerged as the top revenue drivers, significantly outperforming common variants like Robusta.
4. **Market Distribution:** The United States market accounted for the vast majority of sales (**$35,638.89**), completely dwarfing Ireland ($6,696.87) and the United Kingdom.

## Actionable Recommendations
* **Assortment Optimization:** Reallocate inventory purchasing budgets and shelf space to prioritize Light roast coffee and 2.5kg packaging sizes to maximize inventory turnover and profit margins.
* **Conversion-Driven Marketing:** Design targeted promotional campaigns (e.g., exclusive bundle discounts on 2.5kg packages) aimed at incentivizing high-spending non-members to join the loyalty program.
* **VIP Relationship Management:** Establish dedicated account management policies for the Top 5 highest-grossing customers (e.g., Allis Wilmore, Brenn Dundredge) to secure long-term wholesale/B2B revenue streams.
