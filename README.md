# Indian-Housing-Market-Trend-Analysis
This repository contains a comprehensive Power BI End-to-End Project focused on the Indian Housing Market. By synthesizing data from the National Housing Bank (NHB), Knight Frank, and Kaggle, this dashboard provides a data-driven look at how urbanization, infrastructure projects, and interest rates are reshaping the Indian residential landscape
Project Objective
The primary goal is to transform fragmented real estate datasets into actionable intelligence. The dashboard helps users understand where the House Price Index (HPI) is peaking, which cities offer the best Rental Yields, and how the shift toward Luxury Housing is impacting overall market inventory.
Key Analytical Pillars
Price Appreciation & Forecasting: Visualizes the National HPI trends, highlighting the 2025–2026 surge in Delhi NCR (8.3% growth) and Bengaluru (7%).
Supply vs. Demand Dynamics: Tracks the Quarters to Sell (QTS) across Tier-1 cities to identify "overheated" vs. "buyer-friendly" markets.
Segment Performance: A comparative analysis of Affordable vs. Luxury segments, showcasing the recent jump in high-ticket property sales (now 25% of new launches).
Investment Intelligence: Heatmaps identifying high-yield corridors (e.g., Kolkata's 6.32% yield) and price-per-square-foot benchmarks across various BHK configurations.
Technical Implementation
Data Engineering: Utilized Power Query for advanced ETL—standardizing diverse city-wise price units (Lakhs vs. Crores) and cleaning null values in "Year Built" and "Amenities."
Data Modeling: Implemented a Star Schema with centralized Fact tables for sales and Dimension tables for Geography, Calendar, and Property Types.
Advanced Analytics (DAX): Engineered complex measures for YoY Growth, Moving Averages, and Price-to-Income ratios.
UX/UI Design: Features custom tooltips, drill-through actions for granular neighborhood views, and dynamic slicers for BHK size, City, and Furnishing status.
