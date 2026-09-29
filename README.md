# Nova Pharma Global — Business Performance Analysis

## Project Overview 

This project analyzes Nova Pharma Global's business performance across revenue, profitability, regional and product performance, marketing, and supply chain operations. The analysis was developed in Power BI to provide a structured view of business performance, identify important trends and performance gaps, and support data-driven decision-making.

## Business Context

Nova Pharma Global operates across multiple regions, products, customer segments, and sales channels. Understanding overall revenue alone is not enough to evaluate business performance; profitability, growth, target achievement, commercial leakage, marketing returns, and supply chain performance also need to be considered.

This analysis was developed to provide a consolidated view of these areas and identify patterns, performance gaps, and areas that may require further business attention.


## Business Questions

The analysis focuses on answering the following questions:

- What does the overall business performance look like across revenue, profit, regions, and products?
- How is revenue and profit distributed across regions, products, and customer segments?
- How has business performance changed over time, and how does actual performance compare with targets?
- Which regions and products are driving growth and profitability?
- Where are commercial pressures such as discounts, rebates, and revenue leakage occurring?
- How effectively is marketing spend translating into campaign returns?
- Where is stock-out exposure concentrated, and what is its potential revenue impact?
- How is profit contribution distributed across sales channels and sales representatives?

  ## Tools & Skills Used
  
- **Power BI** — data modelling, analysis, dashboard development and visualization
- **Power Query** — data preparation and transformation
- **DAX** — calculated measures, KPIs, growth metrics and performance analysis
- **Data Visualization & Storytelling** — translating business metrics into an executive four-page reporting structure

## Data Source

The analysis was conducted using a pharmaceutical business dataset covering multiple areas of business performance, including sales, products, regions, customers, marketing activities, sales channels, and supply chain operations.

The dataset contains records across 2024 and 2025, allowing performance to be examined across time as well as across different commercial and operational dimensions.

## Data Preparation and Modelling

The dataset was prepared in Power Query to improve data quality and consistency before analysis. Key preparation steps included:

- Promoting headers and assigning appropriate data types across tables.
- Trimming and cleaning text fields across customer, product, region, market, and sales representative tables.
- Identifying and removing duplicate records from dimension tables.
- Standardizing and rounding numerical fields such as revenue, profit, rebates, and discounts.
- Recalculating missing discount values in the Fact Sales table using available sales fields, while retaining existing valid discount values.
- 
##  Data Modelling
The model was structured around the Fact_Sales table, which contains the transactional sales data. It was connected to the relevant dimension tables using primary key–foreign key relationships, allowing the dimensions to filter and provide context to the sales transactions. A separate Targets table was also incorporated to support actual-versus-target analysis.



## Dashboard Analysis

The Power BI report is structured across four pages, moving from an overall view of business performance to growth and profitability, commercial performance, and operational outcomes.

### Business Overview

Provides a high-level view of revenue and profit contribution across products, countries, and regions, establishing the overall performance baseline for the analysis.



### Executive Growth & Profitability

Examines how revenue and profit changed over time, alongside profit margins, target achievement, and product growth, to assess whether overall business growth translated into stronger profitability and progress toward targets.



### Regional & Commercial Performance

Examines profitability and commercial performance across regions, products, and customer segments, with a focus on profit margins, discounts, rebates, and revenue leakage.



### Marketing & Supply Chain Outcome

Evaluates marketing efficiency and operational performance through campaign ROI, stock-out exposure, sales-channel contribution, and sales representative performance.


