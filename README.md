# E-Commerce Growth Analytics Dashboard

## Project Overview

A UK-based online retailer generated more than half a million transactions between December 2009 and December 2010. The volume of data was not the problem; the challenge was understanding what the data was saying.

This project analyzes **525,462 raw transactions** to uncover the company's revenue drivers, customer behavior, product concentration, and potential growth risks.

After data cleaning and validation, **399,569 revenue-generating transactions** from **4,285 customers** were analyzed, representing **$8.64M in total revenue**.

The analysis was built with **Microsoft Excel** and **Power BI**, moving from raw transactional data to business-focused insights and recommendations.

## Business Problem

The company had substantial transactional data but limited visibility into the questions that mattered most to growth:

- Which customers contribute the most value?
- When does revenue accelerate or decline?
- Which products drive the majority of sales?
- How much revenue is exposed to customers at risk of churn?
- How dependent is the business on a single market?
- Where should management focus its next growth and retention efforts?

The objective was to turn transactional records into a clear view of where revenue comes from, where risk exists, and where the business can act.

## Analytical Approach

The project followed an end-to-end analytical workflow:

1. **Data cleaning and validation**
   - Removed invalid and non-revenue transactions.
   - Identified duplicates and data-quality issues.
   - Prepared the dataset for analysis.
2. **Revenue analysis**
   - Analyzed revenue trends over time.
   - Identified seasonal patterns and peak periods.
   - Evaluated average order value and customer contribution.
3. **Customer analysis**
   - Applied RFM analysis to segment customers by recency, frequency, and monetary value.
   - Identified high-value, regular, and at-risk customer groups.
4. **Product analysis**
   - Applied Pareto/ABC analysis to understand revenue concentration across products.
   - Identified products that contribute disproportionately to revenue.
5. **Geographic analysis**
   - Examined revenue distribution across markets.
   - Assessed the company's dependence on the UK market.
6. **Dashboard development**
   - Built an interactive Power BI dashboard to bring the analysis together.
   - Designed KPIs, trends, segmentation, and geographic views around the key business questions.

## Key Findings

### Revenue Was Highly Seasonal

The company generated **$8.64M in revenue**, but performance was not evenly distributed throughout the year.

November was the strongest month at approximately **$1.15M**, while February was the weakest at approximately **$497K**.

The concentration of revenue toward Q4 suggests that the business should enter its peak season with strong inventory availability, customer retention efforts, and marketing preparation already in place.

### A Large Share of Customers Was at Risk

RFM segmentation revealed:

- **13.82%** VIP customers
- **46.18%** Regular customers
- **40%** At-Risk customers

The most concerning figure is the 40% at-risk segment. With revenue already concentrated around the final quarter of the year, losing a significant portion of existing customers before peak season could weaken one of the company's most important revenue periods.

This makes customer retention a strategic priority, not simply a marketing activity.

### Revenue Was Concentrated in a Small Product Portfolio

The product analysis revealed a strong Pareto effect:

- **22%** of products generated approximately **80%** of revenue.
- **52%** of products contributed only **5%** of revenue.

This creates a clear opportunity to differentiate how products are managed. High-performing products should receive greater attention in inventory planning, availability, and marketing, while low-performing products should be evaluated for bundling, repositioning, or removal.

### The Business Was Highly Dependent on the UK

Approximately **89% of revenue came from the UK**.

While the UK represents a strong core market, this level of concentration creates geographic risk. Future growth could come from strengthening existing international markets and identifying regions where the company can expand without relying so heavily on its primary market.

### Order Value Presented an Upselling Opportunity

The average order value was approximately **$456**.

This provides an opportunity to increase customer value through strategies such as product bundling, cross-selling, and targeted recommendations. Rather than relying solely on acquiring more customers, the company could also increase revenue by generating more value from existing customers.

## Strategic Recommendations

Based on the analysis, five priorities emerged:

1. **Launch retention campaigns before Q4** â€” Target at-risk customers before the company's strongest revenue period.
2. **Protect high-performing products** â€” Prioritize Class A products in inventory planning, availability, and marketing.
3. **Optimize low-performing products** â€” Evaluate Class C products for bundling, repositioning, discounting, or removal.
4. **Increase customer value** â€” Use cross-selling and bundling strategies to increase average order value.
5. **Reduce geographic concentration** â€” Develop international markets to create a more diversified revenue base.

## Dashboard

The Power BI dashboard brings the analysis into a single decision-making view. It includes:

- Revenue, orders, customers, and AOV KPIs
- Monthly revenue and seasonality trends
- RFM customer segmentation
- ABC/Pareto product analysis
- Geographic revenue distribution
- Interactive filters for deeper exploration

## Tech Stack

| Tool | Purpose |
| --- | --- |
| Microsoft Excel | Data cleaning and preprocessing |
| Power BI | Data modeling, DAX measures, analysis, and visualization |

## Repository Contents

| File or directory | Description |
| --- | --- |
| `ecommerce_sample.csv` | Sample dataset |
| `ecommerce_dashboard.pbix` | Interactive Power BI dashboard |
| `Analysis_Report.xlsx` | Detailed analysis and findings |
| `Documentation` | Full project documentation |

## What This Project Demonstrates

- Data cleaning and quality validation
- Business-focused exploratory analysis
- KPI development
- RFM customer segmentation
- Pareto/ABC product analysis
- Revenue and seasonality analysis
- Geographic performance analysis
- Power BI dashboard development
- Translating analytical findings into business recommendations

## Outcome

The analysis moves beyond describing what happened to identify where the business is exposed and where management can act.

The central finding is clear: the company has strong revenue potential, but that revenue is concentrated across a small product portfolio, a narrow geographic market, and a business heavily dependent on its peak season.

The opportunity is therefore not simply to sell more. It is to protect the customers, products, and markets already driving growth while building a more resilient revenue base.
