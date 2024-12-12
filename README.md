# Nigeria-Agro-Export-Analysis
This project is focused on managing and analyzing data related to Nigeria's agro export industry withiin 2020 to 2023. It leverages SQL for data cleaning, table joins, and advanced queries, Power BI for interactive data visualizations, and Git for version control and collaboration. The system tracks exporting companies, exported products,product trends, export destinations, and key performance metrics, providing insights to enhance decision-making and improve the efficiency of Nigeria's agro export operations.

![agroexport-removebg-preview](https://github.com/user-attachments/assets/c382fbb6-36d5-4590-a526-a34b1d503cf9)   ![nig agro](https://github.com/user-attachments/assets/e134af53-b658-460e-bc2a-b374be31e7c1)

## Key Features
**Company Database**: Manage comprehensive details of Nigerian companies involved in agro exports.
**Export Tracking**: Record and analyze export activity, including dates, destination countries, ports, and export values.
**Profitability Metrics:** Track key metrics such as profit, units sold, and export value for each transaction.
**Product Management:** Maintain a database of agro products available for export.
**Reporting and Analytics:** Use Power BI to create insightful dashboards showcasing trends, company performance, and export efficiency.

## Tools and Technologies
**SQL:** Cleaned and joined tables to ensure data integrity and consistency for reporting.
**Power BI:** Built interactive visualizations to display export trends and profitability metrics.
**Git:** Used for version control and collaborative project management.

## Database Structure
### 1. Companies
Stores details about Nigerian companies engaged in agro exports.
company_id: Unique identifier for each company (Primary Key).
company_name: Name of the company.
### 2. Products
Contains details about agro products available for export.
product_id: Unique identifier for each product (Primary Key).
product_name: Name of the product.
category: Product category (e.g., Rubber,Cassava,Cashew).
### 3. Export Basic
Captures high-level details of export transactions.
export_id: Unique identifier for each export (Primary Key).
company_id: Foreign key referencing the Companies table.
export_date: Date of the export.
export_country: Country where the goods were exported.
### 4. Export Detailed
Provides additional details for each export transaction.
unit_sold: Number of units sold in the export transaction.
profit: Profit made from the export transaction.
export_value: Total value of the export.
destination_port: Port where the goods were shipped.
## Future Enhancements
- Development of APIs for seamless integration with external systems.
- Machine learning models to predict export trends and optimize pricing strategies.

