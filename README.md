# AI-Driven E-Commerce Customer Segmentation & Retention Analytics 🚀📊

## Project Overview
This end-to-end Data Analytics project aims to solve a real-world business problem: **identifying valuable customers and spotting those at risk of churning**. Instead of relying on manual rule-based segmentation, this project utilizes a Machine Learning approach combined with RFM (Recency, Frequency, Monetary) analysis to automatically group customers based on their purchasing behavior. 

## Tech Stack 🛠️
* **Database Management:** Microsoft SQL Server (SSMS)
* **Machine Learning & Data Processing:** Python (Pandas, Scikit-Learn) via Google Colab
* **Data Visualization & Modeling:** Power BI (DAX, Cross-filter Data Modeling)

## Project Workflow 🔄
1. **Data Extraction & Storage (SQL Server):** 
   - Imported raw global e-commerce transaction data (2000+ records) into MS SQL Server.
   - Queried and validated the data to ensure data integrity before exporting for analysis.

2. **RFM Analysis & AI Segmentation (Python):**
   - Calculated **Recency, Frequency, and Monetary** scores for each customer.
   - Applied the **K-Means Clustering algorithm** to segment the customer base into 4 distinct data-driven groups:
     - 🏆 **VIP / Champions**
     - 😊 **Regular Customers**
     - ⚠️ **At-Risk**
     - ❌ **Lost Customers**

3. **Executive Dashboard Uruvaakkam (Power BI):**
   - Designed an interactive dashboard using a professional 'Z-Pattern' layout.
   - Established **two-way cross-filter data modeling** to connect the raw sales data with the AI-generated clusters.
   - Utilized **DAX** to create dynamic measures and KPIs, enabling drill-down capabilities by Date and Customer Name.

## Key Insights 💡
* The ML clustering model successfully isolated the top-performing customers without manual threshold setting.
* **VIP Customers** were found to drive the majority of the business, generating over **$146K+** in total revenue.
* The interactive dashboard enables the management team to drill down into specific months or search for individual customers to track their segment and purchasing history in real-time.

## Files in this Repository 📂
* `global_ecommerce.csv` - The original dataset.
* `Customer_Segmentation_RFM.ipynb` - The Google Colab notebook containing the Python code for RFM calculation and K-Means clustering.
* `Final_RFM_Clusters.csv` - The segmented output data generated from the ML model.
* `Project.pbix` - The Power BI dashboard file.
