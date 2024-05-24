# RFM-Segmentation-analysis
This repository contains the code and analysis for performing RFM (Recency, Frequency, Monetary) segmentation on a sales dataset. The goal of this project is to categorize customers based on their purchasing behaviors, allowing for targeted marketing strategies and better customer relationship management.
readme_content = """
# RFM Segmentation Analysis on Sales Data

## Project Description

This repository contains the code, analysis, and visualizations for performing RFM (Recency, Frequency, Monetary) segmentation on a sales dataset. The goal of this project is to categorize customers based on their purchasing behaviors, allowing for targeted marketing strategies and better customer relationship management.



![Designer (1)](https://github.com/MudassirAhmed744/RFM-Segmentation-analysis/assets/73222691/c2db2b97-0dd1-4430-81f1-e41a9e4b479b)








## Dataset

The dataset, `sales_data_sample`, includes sales transactions with various attributes such as:

- **ORDERNUMBER**: Unique identifier for each order
- **SALES**: The revenue generated from each sale
- **CUSTOMERNAME**: Name of the customer
- **ORDERDATE**: Date when the order was placed
- **STATUS**: Status of the order (e.g., Shipped, Cancelled)
- **YEAR_ID**: Year of the order
- **PRODUCTLINE**: Category of the product sold
- **COUNTRY**: Country of the customer
- **DEALSIZE**: Size of the deal (e.g., Small, Medium, Large)
- **TERRITORY**: Sales territory

## Analysis Overview

### Data Exploration

- Extracted distinct values for key columns (`status`, `year_id`, `PRODUCTLINE`, `COUNTRY`, `DEALSIZE`, `TERRITORY`) to understand the dataset's dimensions and potential visualization opportunities.
- Grouped and summarized sales data by `PRODUCTLINE`, `YEAR_ID`, and `DEALSIZE` to analyze revenue distribution.

### Sales Performance Analysis

- Identified the best sales months and the total revenue generated in those months.
- Analyzed product sales for peak months to determine which products contributed most to revenue.

### RFM Segmentation

- **Recency**: Calculated the days since the last purchase for each customer.
- **Frequency**: Counted the total number of orders made by each customer.
- **Monetary**: Summed the total sales value for each customer.
- Used NTILE to divide customers into quartiles for each RFM dimension.
- Combined the RFM scores to create customer segments, such as loyal customers, new customers, and potential churners.

### Additional Insights

- Analyzed frequently sold product combinations by examining orders with multiple products.
- Determined the city with the highest sales within a specific country.
- Evaluated the best-selling product lines in the USA by year.

## Key Findings

- Identified top-performing product lines and their contribution to total revenue.
- Highlighted the best months for sales and the leading products in those periods.
- Segmented customers into actionable categories to inform marketing strategies.
- Discovered common product bundles to enhance cross-selling opportunities.
- Identified top cities for sales within specific countries and best product lines in the USA.

## Visualizations

The project includes Tableau visualizations to provide a more intuitive understanding of the analysis. These visualizations help to:

- Visualize the distribution of sales across different product lines, countries, and deal sizes.
- Highlight the best months for sales and the performance of different product lines during those periods.
- Showcase the RFM segmentation and customer categorization.
- Display geographical insights, including top-performing cities and product lines in specific countries.

### How to Access the Visualizations

1. **Tableau Public**: You can access the Tableau visualizations via Tableau Public at [Link](https://public.tableau.com/app/profile/mudassir.ahmed6202/viz/RFMSegmentationAnalysis_17165820239440/Indroduction).
2. **Tableau Workbooks**: The Tableau workbook files (`.twb` or `.twbx`) are included in the `visualizations` folder of this repository.

## Repository Structure

- **SQL Scripts**: Contains SQL queries used for data extraction, transformation, and analysis.
- **Results**: Summarized results of key analyses and segmentation insights.
- **Visualizations**: Tableau workbook files for visualizing the analysis.
- **Documentation**: Detailed explanations of the methodology, findings, and business implications.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/rfm-segmentation-analysis.git
