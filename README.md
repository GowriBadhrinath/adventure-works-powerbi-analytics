# adventure-works-powerbi-analytics
End-to-end Power BI portfolio project transforming raw Adventure Works data into actionable business insights
## 📊 Project Overview
This project demonstrates advanced data modeling, DAX engineering, and UI/UX best practices in Power BI. It focuses on the sales, product, and customer operations of Adventure Works, a fictional global bicycle manufacturing company operating in both B2B and B2C channels.

## 📈 Dashboard Architecture & Insights
The Power BI report is divided into target analytical sections
*  **Executive Summary**: High-level KPIs tracking total revenue, overall profit margins, and order volume against corporate targets.
*  **Sales & Territory Performance**: Geo-spatial analysis highlighting top-performing regional markets and underperforming sales territories.
*  **Product Analytics**: Deep dive into inventory turnover, top-selling bicycle models, and accessory cross-selling trends.
*  **Customer Demographics**: Segmenting the customer base by income brackets, occupation, age group, and purchasing frequency to assist marketing teams

## 🚀 Key Features
* **Star Schema Data Modeling**: Formed clean relationships between fact table and dimension tables. 
* **Advanced DAX Calculations**: Developed custom measures for time-intelligence (YoY Growth, MoM Variance, Moving Averages), profit margins, and dynamic ranking.
* **Interactive UI/UX Design**: Integrated page navigation, dynamic tooltips, parameter switches (for changing metrics on the fly), and bookmark panes.
*  **Row-Level Security (RLS)**: Set up role-based data filtering to mimic real-world territory management security restrictions

## 🛠️ Tools & Technologies Used
* **MySQL Database/Excel**: Source data formats hosting the raw transactional tables from Adventure Works.
* **Power BI Desktop**: For data modeling and visual dashboard creation.
* **Power Query**: For importing tables and filtering data directly via MySQL connectors.
* **DAX (Data Analysis Expressions)**: For creating custom calculated columns and measures.


## 📁 Repository Structure
* `/Report`: Contains the main `.pbix` Power BI file.
* `/Data-Model`: Images of Star Schema for quick preview.
* `/Excel`: Contains the `.xlsx` files.
* `/Screenshots`: Images of the dashboard pages for quick preview.


## 💻 How to View the Dashboard
1. Clone this repository to your local machine.
2. Review the data files inside the `/Excel` folder.
3. Open the `.pbix` file located in the `/Report` folder using [Power BI Desktop](https://microsoft.com).
