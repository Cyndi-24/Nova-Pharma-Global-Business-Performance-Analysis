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

![image alt](https://github.com/Cyndi-24/Nova-Pharma-Global-Business-Performance-Analysis/blob/main/Nova%20Pharma%20global/Nova%20Pharmonava%20images/Data_modelling.png)

## Analysis and Visualization 

The Power BI report is structured across four pages, moving from an overall view of business performance to growth and profitability, commercial performance, and operational outcomes.

### Business Overview

Provides a high-level view of revenue and profit contribution across products, countries, and regions, establishing the overall performance baseline for the analysis.

![image alt](

### Executive Growth & Profitability

Examines how revenue and profit changed over time, alongside profit margins, target achievement, and product growth, to assess whether overall business growth translated into stronger profitability and progress toward targets.



### Regional & Commercial Performance

Examines profitability and commercial performance across regions, products, and customer segments, with a focus on profit margins, discounts, rebates, and revenue leakage.



### Marketing & Supply Chain Outcome

Evaluates marketing efficiency and operational performance through campaign ROI, stock-out exposure, sales-channel contribution, and sales representative performance.

## Analytical Questions 

### 1. What does the overall business performance look like across revenue, profit, regions, and products?

Nova Pharma generated $486.39M in revenue at a 37.86% profit margin. Europe was the largest contributor to both revenue and profit, while Product 35 led cumulative revenue, showing where the strongest overall contributions came from.

### 2. How is revenue and profit distributed across regions, products, and customer segments?

Revenue and profit are more concentrated in the leading regions, particularly Europe, while customer-segment profit is comparatively balanced. Public, SME, and Enterprise customers contribute 35.22%, 33.92%, and 30.86% respectively, indicating that profitability is not heavily dependent on a single customer segment.

### 3. How has business performance changed over time, and how does actual performance compare with targets?

Revenue grew by 6.88% YoY, while profit increased by 6.07%, indicating positive business growth. However, target achievement remained at only 13.25%, showing a substantial gap between actual growth and planned performance.

### 4. Which regions and products are driving growth and profitability?

South America recorded the strongest improvement in profit margin, while the Middle East experienced the largest decline. At product level, Products 19 and 8 stood out with strong growth in both revenue and profit, making them key contributors to profitable growth.

### 5. Where are commercial pressures such as discounts, rebates, and revenue leakage occurring?

Europe recorded the highest absolute revenue leakage at $329.22K, while the Middle East recorded the lowest at $89.74K. However, Europe also has the largest revenue base, so absolute leakage alone does not indicate weaker performance. At product level, higher discounts did not consistently correspond with lower profit margins, suggesting that discounting alone does not explain differences in product profitability.


### 6. How effectively is marketing spend translating into campaign returns?

Marketing campaigns generated an average ROI of 2.39, but higher spending did not consistently translate into higher returns. Campaign 15 achieved the highest ROI of 3.78 on a marketing spend of $174.60K, showing that campaign effectiveness was not determined by spend level alone.


### 7. Where is stock-out exposure concentrated, and what is its potential revenue impact?

Stock-out exposure was highest in Oncology, followed by Diabetes and Pain. Products affected by stock-outs recorded a combined $18.87M gap between forecast and actual revenue, indicating potential revenue exposure rather than confirmed revenue lost directly to stock-outs.

### 8. How is profit contribution distributed across sales channels and sales representatives?

Profit contribution was well distributed across sales channels, with Retail Pharmacy leading at 21.36% and Distributor contributing the lowest share at 18.91%. Sales representative performance showed greater variation, with Rep 17 generating the highest profit contribution at approximately $5.8M.

## Recommendations

- **Prioritize profitable growth products:** Support Products 19 and 8 with appropriate commercial resources, as both demonstrated strong revenue and profit growth.

- **Strengthen performance in the Middle East:** Focus commercial efforts on improving margins in the region while protecting the margin gains recorded in South America.

- **Prioritize inventory availability in high-exposure drug classes:** Give Oncology, Diabetes, and Pain greater priority in replenishment planning to reduce stock-out exposure and protect potential revenue.

- **Prioritize higher-return marketing campaigns:** Direct future marketing budgets toward campaigns delivering stronger ROI, rather than allocating more resources based on spending levels alone.

- **Strengthen revenue-leakage controls:** Closely monitor and reduce revenue leakage, particularly in Europe, while assessing leakage relative to regional revenue to account for differences in market size.

  
## Limitations

- The stock-out revenue shortfall is an estimated exposure based on the gap between forecast and actual revenue for products that experienced stock-outs. It should not be interpreted as confirmed revenue lost directly because of stock-outs.

- The analysis covers the available 2024–2025 period, limiting the ability to assess longer-term performance trends beyond these two years.

- The analysis identifies performance patterns and relationships within the available data, but some underlying business drivers—such as the reasons behind regional margin changes or differences in campaign performance—cannot be determined from the available variables alone.

## Conclusion

The analysis provides a consolidated view of Nova Pharma’s performance, highlighting opportunities to strengthen profitable growth, regional performance, marketing returns, commercial controls, and inventory availability.
