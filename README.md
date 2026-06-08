# Sales Dashboard Project

## Project Overview

This repository hosts a multi-channel e-commerce sales and profitability analysis project built within a spreadsheet architecture. The main purpose of the project is to aggregate fragmented operational transaction logs into a centralized dashboard to track organizational revenue, profit margins, and logistics efficiency. By providing interactive slicing filters across product segments, geographical regions, and payment channels, this project solves the issue of delayed financial reporting, allowing retail stakeholders to identify profitable sub-categories and locate supply chain bottlenecks

## Requirements

Microsoft Excel (2019, 2021, or Microsoft 365 recommended)

System Memory: Minimum 4 GB RAM (8 GB recommended for large data rows)

Operating System: Microsoft Windows or macOS

Prerequisites: Advanced Excel features enabled (Pivot Tables, Slicers, and Data Visualization Charts)

## Tools and Technologies

Core Spreadsheet Platform: Microsoft Excel

Data Aggregation & Structuring: Excel Pivot Tables

Interactivity Control: Excel Slicers (Dynamic Cross-Filtering)

Visualization Layer: Excel Pivot Charts (Clustered Bar, Donut, Line, and Tree-map variations)

## Challenges Faced

Chart Overcrowding on Sub-Category Counts: Plotting dozens of individual product sub-categories along a single axis caused text overlapping and crowded data series. This layout limitation was overcome by implementing a secondary sorting filter to limit the view to core items while arranging the categories by volume.

Synchronized Slicer Connections: Ensuring that a single slicer selection (such as Region or Product Category) instantly updated multiple independent charts required careful configuration of pivot table connections. The data architecture was adjusted by linking all visual elements back to standardized data sheets.

Dual-Axis Synchronization: Presenting volume metrics alongside percentage margins on a single combo chart created distorted scales. This challenge was resolved by mapping percentage changes to a distinct secondary vertical axis while using explicit number formatting on the data labels.

## Key Insights

![image alt](https://github.com/rt5899-art/Sales-Dashboard-Excel/blob/main/ss-%20Sales%20dashboard_excel.png?raw=true)

Based on the aggregated data compiled in the spreadsheet dashboard interface, the following performance trends were identified:

High-Level Financial Performance Indicators: The business achieved a Total Sales volume of 5604598.96, yielding an overall Total Profit of 1312009.3.

Perfect Split in Sales Channels: Consumer engagement between marketing methods reflects an exact 50% / 50% equilibrium, where Online and Offline channels contribute identical revenue splits to the organization.

Balanced Payment Method Distribution: Payment processing methods show highly uniform usage. Cards lead at a 26% share, followed closely by Cash on Delivery (COD) at 25%, UPI payment gateways at 25%, and digital Wallets representing the remaining 24% share.

Geographical Revenue Distortions: Total regional sales performance indicates an extreme imbalance. The East region stands out as the primary revenue generator, accounting for 100% of the recorded sales distribution on the regional Pareto-style visual (representing the full 56,04,599 value scale). In contrast, Central, North, South, and West regions reflect a 0% baseline contribution.

Temporal Revenue Flow Patterns: Monthly revenue tracking over the calendar year demonstrates a highly cyclical pattern. The first quarter opens with a high-volume peak, led by January at 13.86%, followed by February at 12.29%, and March at 12.63%. Revenue settles into a lower baseline during the spring and summer months (averaging between 5.91% and 7.45%) before dipping to a low layout entry point during December at 7.79%.

Logistics and Delivery Status Realization: Delivery tracking highlights operational inefficiencies across fulfillment channels. While the largest portion of items achieved a status of Delivered at 1389004.79, In-Transit stock ties up 1567078.87 in value. Furthermore, Cancelled orders cost the business 1324920.18, while Returned items account for another 1323595.12.

Sub-Category Sales Performance: Evaluated individual items reflect a highly competitive mix. Individual category highlights include Face Cream leading the pricing performance bands at 9.59% and Mobile at 9.58%, closely matched by Jacket at 8.86%, Perfume at 8.77%, and Laptop at 8.61%.

## Recommendations for Improvements

Restructure Regional Reporting Foundations: The dashboard highlights that 100% of captured sales (56,04,599) are mapped to the East region, while Central, North, South, and West return 0%. The data import connections must be audited to ensure that regional transactions from other territories are not being misclassified or dropped during extraction.

Establish a Dedicated Order Retention Workflow: Cancelled orders (1324920.18) and Returned inventory (1323595.12) are stripping away over 2.6M in potential value. A customer follow-up protocol and quality assurance verification should be initiated to reduce these cancellations and returns by a target of 15-20%.

Accelerate In-Transit Shipping Cycles: In-Transit stock currently locks up 1567078.87 in capital—the single largest bucket in delivery status. Third-party logistics contracts should be audited to improve delivery speed, moving these delayed orders into "Delivered" status to shorten cash-flow cycles.

Capitalize on First Quarter Seasonal Surges: Because January (13.86%), February (12.29%), and March (12.63%) represent the strongest sales window, inventory levels and marketing budgets for top-performing lines like Face Cream (9.59%) and Mobile (9.58%) should be scaled up ahead of this peak to maximize seasonal revenue.
