# Telco Customer Churn Analysis Dashboard

Interactive Power BI dashboard analyzing 7,043 telecom customers to identify churn drivers and revenue impact.

## Project Overview

Built a comprehensive three-page Power BI dashboard to analyze customer churn patterns in the telecommunications industry, identify key risk factors, and provide actionable retention strategies.

## Key Findings

- **26.5% overall churn rate** resulting in **$139,127 monthly recurring revenue at risk**
- Month-to-month contracts show **42% churn** compared to only **3% for two-year contracts**
- **First 12 months** account for approximately 50% of all churn
- Customers with Fiber Optic internet **without security services** show 2x higher churn rates
- Churned customers paid **$13 more per month** on average ($74 vs $61)
- High-risk customer profile: New customers (<20 months tenure), paying $80+/month, singles without dependents

## Business Recommendations

1. **Implement early-stage retention program** targeting customers in their first 12 months
2. **Incentivize annual contract conversions** through promotional discounts
3. **Bundle security and tech support services** with Fiber Optic internet packages
4. **Review pricing strategy** for high-value customer segments ($70+/month)
5. **Develop targeted campaigns** for single, senior customers without dependents

## Dashboard Structure

### Page 1: Executive Summary

**Purpose:** High-level overview of churn metrics and trends

**Key Metrics:**
- Total Customers: 7,043
- Churned Customers: 1,869
- Churn Rate: 26.54%
- Monthly Revenue Lost: $139,127
- Average Customer Tenure: 32 months

**Visualizations:**
- KPI cards displaying critical business metrics
- Donut chart showing customer retention overview (73.46% retained vs 26.54% churned)
- Stacked column chart analyzing churn by contract type
- Line chart showing churn rate trends across customer tenure
- Bar chart comparing average monthly charges between churned and active customers
- Interactive slicers for contract type, internet service, payment method, and gender

**Key Insight:** Month-to-month contract holders have 14x higher churn rate than two-year contract customers, with highest risk occurring in the first year of service.

---

### Page 2: Service Analysis

**Purpose:** Identify which services impact customer retention

**Analysis Coverage:**
- Phone Service
- Internet Service Type (Fiber Optic, DSL, No Internet)
- Online Security
- Tech Support
- Online Backup
- Device Protection
- Streaming TV
- Streaming Movies

**Key Insights:**
- Fiber Optic internet users: 42% churn vs 19% for DSL users
- "Protective services" (online security, tech support, backup) reduce churn by approximately 27 percentage points
- Customers with 4+ services show only 15% churn compared to 60% for those with 0-1 services
- Streaming services (TV/Movies) have minimal impact on customer retention
- Service bundling significantly improves retention rates

---

### Page 3: Demographics & Financial Impact

**Purpose:** Understand customer demographics and financial patterns

**Analysis Components:**

**Demographic Breakdown:**
- Senior citizen status and churn correlation
- Partner status impact on retention
- Dependents influence on customer loyalty

**Financial Analysis:**
- Scatter plot visualization revealing "danger zone": high monthly charges ($80-$120) combined with low tenure (<20 months)
- Monthly charge distribution by customer segment
- Revenue impact breakdown

**Key Insights:**
- Senior citizens show 42% churn vs 23% for non-seniors
- Customers without partners: 33% churn vs 20% with partners
- Customers without dependents: 31% churn vs 16% with dependents
- High-value customers who survive first 20 months become highly loyal
- $456K total monthly revenue with $317K from active customers and $139K at risk

## Tools & Technologies

- **Power BI Desktop** - Primary tool for data visualization and dashboard creation
- **Power Query** - Data cleaning, transformation, and preparation
- **DAX (Data Analysis Expressions)** - Created calculated measures and custom columns
- **Data Source:** IBM Telco Customer Churn dataset from Kaggle (7,043 records, 21 features)

## Technical Implementation

### DAX Measures Created:
- Total Customers
- Churned Customers
- Active Customers
- Churn Rate (percentage)
- Average Monthly Revenue
- Monthly Revenue Lost
- Average Tenure
- Total Monthly Revenue
- Active Customer Revenue

### Calculated Columns:
- Tenure Groups (0-1 Year, 1-2 Years, 2-3 Years, 3-4 Years, 4+ Years)
- Monthly Charge Ranges (Under $30, $30-$50, $50-$70, $70-$90, $90+)

### Data Preparation:
- Handled missing values in TotalCharges column
- Standardized data types across all fields
- Created customer segmentation categories
- Implemented cross-filtering for interactive analysis

## Skills Demonstrated

- **Data Visualization:** Designed intuitive, interactive dashboards with 15+ coordinated visuals
- **Business Intelligence:** Translated complex data into actionable business recommendations
- **Data Analysis:** Identified patterns and correlations driving customer churn
- **DAX Programming:** Built sophisticated calculated measures and columns
- **Data Modeling:** Structured data relationships for optimal performance
- **Storytelling:** Created cohesive narrative across three dashboard pages
- **Financial Analysis:** Quantified revenue impact and business risk

## Project Impact

This dashboard enables stakeholders to:
- Quickly identify high-risk customer segments
- Understand the financial impact of churn ($139K monthly revenue at risk)
- Make data-driven decisions on retention strategies
- Target interventions at the most critical customer touchpoints
- Optimize service bundling to improve retention rates

