# Retail and Sales Analysis

## Project Overview

This project presents an end-to-end analysis of a retail sales dataset, focusing on customer purchasing behavior, product demand patterns, and sales performance trends.
The goal is to transform raw transactional data into actionable business insights to support decision-making across marketing, product strategy, and customer engagement.

## Objectives
- Analyze sales performance over time (monthly & quarterly trends)
- Understand customer demographics (age & gender)
- Identify customer purchasing patterns and frequency
- Evaluate product demand and distribution
- Provide strategic business recommendations

## Dashboard Structure

### Page 1: Sales Performance Overview
Focuses on overall business performance.

**KPIs:**
- Total Revenue
- Total Profit
- Profit Margin (%)
- Total Units Sold
  
**Visuals:**
- Monthly Revenue Trend (MoM growth)
- Revenue by Gender
- Revenue by Age Category
- Product Contribution Analysis
- Profitability Overview

## Page 2: Customer Behavior & Product Performance
Focuses on how customers buy and what they buy.

**Visuals:**
- Customer Buying Patterns by Age & Gender
- Product Distribution
- Age-Based Product Demand
- Customer Purchase Frequency Distribution
- Average Items per Purchase by Customer Segment
- Top Products by Purchase Frequency

## Data Cleaning & Preparation
- Converted Date column to datetime format
- Validated revenue and profit calculations
- Created Age Groups and Age Categories
- Built a Date Table for time intelligence (MoM, margin analysis)
- Ensured proper data types and consistency

## Data Model
The project uses a Star Schema Model:
- Fact Table: clean_retail_sales_data
- Dimension Table: Date Table

**Relationship:**
- Date Table (1) → Sales Data (Many)
- Enables accurate time-based analysis (MoM, QoQ, trends)

## Key Insights
- Customers aged 26–35 show the highest purchasing frequency
- Female customers slightly outperform males in total purchases
- Clothing and Electronics are the most demanded product categories
- Middle-aged customers tend to purchase larger quantities per transaction
- Sales peak during certain months, indicating seasonal demand patterns

## Strategic Recommendations
- Engage High-Frequency Customers
- Target active customer segments with loyalty programs and personalized offers to increase retention.
- Tailor Marketing by Customer Segment
- Align campaigns with age and gender preferences to improve engagement and conversion.
- Optimize Product Portfolio
- Focus on high-demand products while improving margins through pricing and bundling strategies.
- Leverage Cross-Selling Opportunities
- Promote complementary products to increase basket size and transaction value.
- Plan Around Seasonal Trends
- Align inventory and promotions with peak sales periods to maximize performance.
- Adopt Data-Driven Customer Segmentation
- Segment customers based on behavior to enable targeted and efficient marketing strategies.

## Dashboard Overview 
![Dashboard Preview](https://github.com/amieecode/retail-and-sales-analysis/blob/main/Images/Retail%20Store%20analysis.png)
![Dashboard Preview](https://github.com/amieecode/retail-and-sales-analysis/blob/main/Images/Retail%20Store%20Analysis%202.png)

## Tools & Technologies
- Power BI – Data visualization & dashboard creation
- Python (Pandas) – Data cleaning & preprocessing
- Excel – Initial data exploration
- DAX – Measures and KPI calculations

# Project Files
- **dataset/** → Raw & cleaned data
- **notebooks/** → Data cleaning & EDA
- **dashboard/** → Power BI dashboard file
- **images/** → Dashboard screenshots

