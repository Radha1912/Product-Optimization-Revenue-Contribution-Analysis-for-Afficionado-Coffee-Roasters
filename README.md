# Product-Optimization-Revenue-Contribution-Analysis-for-Afficionado-Coffee-Roasters
Problem Statement
Although transaction-level product data is available, Afficionado Coffee Roasters lacks:

• Clear visibility into product popularity vs profitability
• Category-level revenue dependency insights
• Identification of low-impact or underperforming menu items
Primary Objectives
• Identify top-selling and least-selling products
• Quantify revenue contribution by product and category
• Measure revenue concentration across the menu
Secondary Objectives
• Support menu simplification and optimization
• Identify high-impact “hero” products
• Highlight low-performing products for review or redesign
Analytical Methodology (Step-by-Step)
Data Ingestion & Validation
• Load transaction-level data
• Validate product identifiers and prices
• Ensure quantities are positive and realistic
Revenue Computation
• Compute revenue at transaction level:
● Revenue = transaction_qty × unit_price
• Aggregate revenue by:
● Product
● Product type
● Product category
Product Popularity Analysis
• Total units sold per product
• Ranking products by sales volume
• Identify top and bottom performers
Revenue Contribution Analysis
• Total revenue per product
• Revenue share (%) of each product
• Comparison between volume rank and revenue rank
Category & Product-Type Performance
• Revenue share by category (Coffee, Tea, Chocolate)
• Product-type contribution within each category
• Dependence analysis on core categories
Revenue Concentration & Menu Balance
• Pareto (80/20) analysis
• Identify:
Revenue anchors (few products driving most revenue)
Long-tail products with minimal impact
• Evaluate menu diversification risk
Streamlit Web Application Requirements
Core Modules
• Product ranking (by volume & revenue)
• Category revenue distribution
• Popularity vs revenue scatter plots
• Product drill-down performance tables
User Capabilities
• Category and product-type filters
• Store location selector
• Top-N product slider
