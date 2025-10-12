8# ☕ Coffee Shop Sales Analysis

![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Dashboard](https://img.shields.io/badge/Dashboard-Interactive-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

## 📊 Project Overview

Analyzed 6 months of transactional data (January-June 2023) from Maven Roasters, a coffee shop chain with three NYC locations, to identify sales patterns and optimize operational efficiency. Built an interactive Excel dashboard that revealed peak transaction hours (7-11 AM) and product performance insights, enabling data-driven staffing and inventory decisions across Astoria, Hell's Kitchen, and Lower Manhattan locations.

---

## 🎯 Business Problem

Maven Roasters, a growing coffee shop franchise with three locations in New York City, needed visibility into their sales performance and operational patterns. As a new franchise owner, the stakeholder required answers to critical questions:

- Which locations are generating the most revenue?
- What are the peak hours for customer traffic at each location?
- Which products are top performers vs. underperformers?
- How do sales trends vary by day of week and throughout the week?
- Are there patterns in product category preferences (Coffee, Tea, Bakery, etc.)?

Without a centralized view of this data, the business couldn't make informed decisions about staffing schedules, inventory management, or location-specific strategies. The raw transactional data from January-June 2023 existed but wasn't actionable in its current form.

---

## 🔍 Methodology

### Data Collection & Preparation
- Collected 6 months of transactional sales data (January-June 2023) from all three Maven Roasters locations
- Dataset included transaction timestamps, product details, categories, prices, and location information

### Data Cleaning & Transformation
- Used `TEXT()` and `HOUR()` functions to extract time components from transaction timestamps for hourly analysis
- Profiled data to identify inconsistencies, missing values, and outliers
- Standardized product names and category classifications across all locations
- Created calculated fields for revenue analysis

### Analysis Techniques
Built multiple **Pivot Tables** to aggregate data by:
- Month for revenue trending
- Day of week for transaction volume patterns
- Hour of day for peak time identification
- Product and product category for performance ranking

Created **Pivot Charts** to visualize key metrics

### Dashboard Development
- Designed an interactive dashboard with location-based **slicer** for dynamic filtering
- Implemented visualizations including:
  - Line chart for monthly revenue trends
  - Bar charts for day-of-week and hourly transaction patterns
  - Horizontal bar chart for product category distribution
  - Top 15 products table with transaction counts and revenue

---

## 🛠️ Skills Demonstrated

### Excel Functions & Features
- `TEXT()` and `HOUR()` functions for date/time manipulation
- Data profiling and cleaning techniques
- Pivot Tables for multidimensional analysis
- Pivot Charts for data visualization
- Slicers for interactive filtering
- Dashboard design and layout

### Analytical Skills
- Time-series analysis (monthly trends, hourly patterns)
- Comparative analysis across locations
- Product performance ranking
- Pattern recognition in customer behavior

### Business Intelligence
- KPI identification and tracking
- Interactive dashboard design
- Data storytelling through visualization
- Actionable insights generation

---

## 📈 Results & Key Findings

### Revenue Performance
- Total revenue showed consistent growth from January ($27,311) to June ($55,083-$56,357 depending on location)
- Revenue increased approximately **100%** over the 6-month period
- All three locations contributed to overall growth

### Transaction Patterns
- **Peak Hours:** 7-11 AM accounts for the highest transaction volume (approximately 6,000-7,000 transactions during hours 7-10)
- **Slowest Period:** Transactions drop significantly after 8 PM (under 2,000 transactions)
- **Busiest Days:** Monday, Wednesday, Thursday, and Friday show consistently higher traffic (around 7,000+ transactions)
- **Slower Days:** Saturday and Sunday have lower transaction volumes (approximately 6,500-6,800 transactions)

### Product Insights
- **Top Product Category:** Coffee dominates with over 20,000 transactions
- **Top 3 Individual Products:**
  1. Barista Espresso (5,320-6,293 transactions, $27,428-$32,420 revenue)
  2. Brewed Chai Tea (5,066-6,233 transactions, $24,009-$27,428 revenue)
  3. Gourmet Brewed Coffee (5,217-6,053 transactions, $23,010-$23,823 revenue)
- Tea category shows strong performance with approximately 13,000 transactions
- Bakery items account for roughly 7,800 transactions

### Location Comparison
The dashboard allows filtering by Astoria, Hell's Kitchen, and Lower Manhattan, revealing location-specific patterns in customer preferences and traffic.

---

## 💡 Business Recommendations

### 1. Staffing Optimization
- Schedule more staff during peak hours (7-11 AM) to handle high transaction volumes
- Reduce staffing after 8 PM when traffic drops significantly
- Consider weekend-specific schedules given lower Saturday/Sunday volumes

### 2. Inventory Management
- Prioritize stock for top-performing items (Barista Espresso, Brewed Chai Tea, Gourmet Brewed Coffee)
- Review and potentially discontinue or reposition lower-performing products (items ranking below top 15)
- Ensure adequate coffee and tea supplies given their dominance in transactions

### 3. Marketing & Promotions
- Launch afternoon/evening promotions (2-8 PM) to boost slower periods
- Create weekend-specific offers to increase Saturday/Sunday traffic
- Promote underperforming product categories during peak hours

### 4. Operational Efficiency
- Prepare ingredients and supplies for top products before morning rush
- Consider express service lanes during 7-11 AM peak hours
- Implement location-specific strategies based on individual performance patterns

---

## 🚀 Next Steps & Future Analysis

### Immediate Actions
- Share dashboard with franchise owners for monthly performance reviews
- Set up automated data refresh process for ongoing monitoring
- Create location-specific reports for individual store managers

### Future Analysis Opportunities
- Analyze customer return rates and lifetime value
- Examine correlation between weather patterns and sales
- Compare performance against industry benchmarks
- Conduct seasonal analysis (add Q3-Q4 data when available)
- Analyze average transaction value and upselling opportunities
- Study product bundle patterns to create combo offers

### Technical Enhancements
- Automate data import using Power Query
- Add more KPIs (Average Transaction Value, Items per Transaction, Customer Retention Rate)
- Create predictive models for demand forecasting
- Develop mobile-friendly dashboard version for on-the-go access


