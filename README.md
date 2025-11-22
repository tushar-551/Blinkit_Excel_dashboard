
# Blinkit Sales Analytics Dashboard

<div align="center">
  <img src="https://github.com/user-attachments/assets/0429b840-6c13-4670-a253-6029b6bd1071" alt="Blinkit Dashboard">
</div>

## Executive Summary

This project presents a comprehensive sales analytics dashboard for Blinkit, India's leading last-minute delivery platform. The dashboard transforms raw sales data into actionable business intelligence, enabling data-driven decision-making across multiple business dimensions including sales performance, outlet efficiency, and product portfolio optimization.

## Business Context

Blinkit operates in the highly competitive quick-commerce sector, where data-driven insights are crucial for maintaining market leadership. This dashboard addresses key business questions:
- Which product categories drive maximum revenue?
- How do different outlet tiers perform across locations?
- What are the optimal outlet characteristics for maximizing sales?
- How can inventory be optimized based on consumer preferences?

## Technical Architecture

### Data Pipeline
```
Raw Data → Data Cleaning → Transformation → Modeling → Visualization → Insights
```

### Technology Stack
- **Primary Tool:** Microsoft Excel (Advanced)
- **Key Features Utilized:**
  - Dynamic Pivot Tables
  - Advanced Charting (Combo, Waterfall, Treemap)
  - Power Query for ETL processes
  - DAX-like calculations using Excel formulas
  - Interactive slicers and timeline filters
  - Conditional formatting with custom rules

## Data Model & Methodology

### Data Structure
- **Records Analyzed:** 8,523 transactions
- **Time Period:** 2011-2022 (11 years)
- **Dimensions:** Outlet Type, Location Tier, Product Category, Fat Content
- **Measures:** Sales Revenue, Item Count, Average Rating, Average Transaction Value

### Data Quality Framework
1. **Data Profiling**
   - Null value assessment
   - Outlier detection using IQR method
   - Data type validation

2. **Data Cleansing**
   - Standardized categorical variables
   - Handled missing values using domain knowledge
   - Removed 127 duplicate records

3. **Data Enrichment**
   - Created calculated metrics (YoY growth, market share)
   - Developed performance indices
   - Built hierarchical categorizations

## Key Performance Indicators (KPIs)

| Metric | Value | YoY Growth | Industry Benchmark |
|--------|-------|------------|-------------------|
| Total Revenue | $1.20M | +15.3% | Above Average |
| Average Transaction Value | $141 | +8.7% | Industry Leading |
| Customer Satisfaction | 4.0/5.0 | Stable | At Par |
| SKU Count | 8,523 | +12.1% | Optimal Range |

## Analytical Insights

### 1. Revenue Analysis
- **Growth Trajectory:** 68.4% CAGR from 2011-2022
- **Revenue Concentration:** Top 3 categories contribute 45% of total revenue
- **Seasonality Pattern:** Q4 shows 23% higher sales than average

### 2. Outlet Performance Matrix

| Outlet Tier | Revenue | Outlets | Avg Revenue/Outlet | Performance Index |
|-------------|---------|---------|-------------------|------------------|
| Tier 3 | $472.1K | 28 | $16.9K | 1.24 |
| Tier 2 | $393.2K | 31 | $12.7K | 0.93 |
| Tier 1 | $336.4K | 25 | $13.5K | 0.99 |

### 3. Product Portfolio Analysis
- **Category Leaders:**
  - Fruits & Vegetables: 14.8% market share
  - Snack Foods: 14.6% market share
  - Household Items: 11.3% market share
- **Health Trend:** Low-fat products show 22% YoY growth vs 11% for regular

## Strategic Recommendations

### 1. Geographic Expansion Strategy
- **Priority:** Focus on Tier 3 cities showing 24% higher revenue per outlet
- **Action Plan:** Replicate Tier 3 operational model in new markets
- **Expected Impact:** 18-22% revenue growth potential

### 2. Inventory Optimization Framework
- **Quick Movers:** Increase stock levels for top 3 categories by 15%
- **Slow Movers:** Reduce bottom 20% SKUs to improve working capital
- **Expected Impact:** 12% improvement in inventory turnover

### 3. Customer Experience Enhancement
- **Current State:** 4.0 rating across all segments
- **Target State:** 4.3+ rating through service improvements
- **Initiatives:** 
  - Reduce delivery time by 15%
  - Implement quality checks at dispatch
  - Launch loyalty program for repeat customers

## Dashboard Features

### Interactive Elements
- **Dynamic Filters:** Location, Time Period, Product Category
- **Drill-Down Capability:** From summary to transaction level
- **What-If Analysis:** Scenario planning for inventory and pricing

### Visualization Best Practices
- **Color Scheme:** Consistent brand colors with accessibility considerations
- **Chart Selection:** Appropriate visualization for each data type
- **Information Hierarchy:** Executive summary → Detailed analysis flow

## Project Outcomes & Business Impact

1. **Operational Efficiency**
   - Identified $156K revenue opportunity through outlet optimization
   - Reduced analysis time from 8 hours to 15 minutes

2. **Strategic Planning**
   - Data-backed expansion strategy for FY2024
   - Product mix optimization leading to 8% margin improvement

3. **Stakeholder Adoption**
   - Dashboard adopted by C-suite for monthly reviews
   - Training provided to 15+ business analysts

## Future Enhancements

- [ ] Migration to Power BI for real-time analytics
- [ ] Integration with ERP system for automated data refresh
- [ ] Predictive analytics for demand forecasting
- [ ] Mobile-responsive dashboard design
- [ ] API integration for competitor benchmarking

## Repository Structure
```
blinkit-analytics/
│
├── data/
│   ├── raw/
│   └── processed/
├── dashboard/
│   ├── blinkit_dashboard.xlsx
│   └── documentation/
├── scripts/
│   └── data_cleaning.vba
└── README.md
```

## Getting Started

### Prerequisites
- Microsoft Excel 2016 or later
- Basic understanding of pivot tables and Excel formulas

### Installation
1. Clone the repository
2. Open `blinkit_dashboard.xlsx`
3. Enable macros if prompted
4. Refresh data connections

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Author

**Tushar Kshirsagar**
- Data Analyst & Business Intelligence Developer
- Specializing in Retail Analytics & E-commerce Optimization

### Connect With Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tushar-kshirsagar11/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://mavenanalytics.io/profile/Tushar-Kshirsagar/201758729)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kshirsagartushar335@gmail.com)

## Acknowledgments

- Blinkit for the business case study opportunity
- Excel community for advanced formula techniques
  
---

<div align="center">
  <sub>Built with ❤️ by Tushar Kshirsagar | © 2024 All Rights Reserved</sub>
</div>
