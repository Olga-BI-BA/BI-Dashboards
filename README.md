# Sales-Reports-
Sales Dashboards on synthetic dataset (Contoso) 

# Contoso Sales Performance Report 📊

An interactive, enterprise-grade Power BI dashboard designed to monitor key performance indicators (KPIs), product and regional efficiency.

> **Project Status:** Completed 🚀  
> **Tech Stack:** Power BI Desktop, Power Query (M Language), DAX, Git LFS.

## 📷 Report Screenshots

### 1. Main Page: Global Sales Overview
This page serves as the strategic cockpit for executive management, offering a high-level performance overview across all global markets, sales channels, and product categories.
<img width="1504" height="843" alt="Animation" src="https://github.com/user-attachments/assets/ebe2197b-f3b8-467c-b6c6-5bc12348b65f" />


**Overall revenue decline hits most markets and channels.**
**Strong growth in small categories hasn't offset revenue lost from large categories shrinking.**

**Macro Regions**
Asia is the only region growing (+8.81%), driven by China (the second-largest market, up +6%) and Japan (+16.77%), with significant growth in Thailand (+64%), South Korea (+61%), and Bhutan (+55%). The USA, the main and largest market, crashed by -15.85% and lost its share in revenue, dropping from 56.7% to 52.5% in 2025. All markets in Europe are still experiencing stagnation (-9.22%).

**Channels**
Online is the only growing channel overall (+1.46%), due to being the main distribution channel in China with stable growth over 2024-2025. Store revenue fell the most (-13.35%), mainly due to overall sales decline in the USA market, where it generates 58% of revenue.

**Categories**
Home Appliances, Computers, Cameras and camrecorders are the revenue & profit backbone, accounting 75.7% of total global revenue. But 2 of these categories (Home Appliances and Cameras and camrecorders) in 2025 are top losers in growth (~ - 22% each). Strong growing categories Games and Toys (+56.54%) and Audio (30.69%) contribute barely $0.1bn and hasn't offset revenue lost from large categories shrinking, so overall revenue is still down 9.05%

### 2. Regional Trends Page

The **Regional Trends** page is built to provide regional managers and stakeholders with deep visibility into geographical performance. It effectively answers the following critical business questions:

*   **Which markets are driving the company's global revenue, and which are shrinking?**
*   **What is the exact financial impact in revenue and profit across different countries?**
*   **How does seasonal sales performance vary across major continents and countries throughout the year?**
*   **What are the operational footprints within specific countries?**
*   **How do these regional trends shift when filtering by specific years or distribution channels?**


  >Technical Features Demonstrated: Bookmarks, Bottoms, Filtering, Visual Interactions, DAX, Visual Calculations, Conditional Formatting, Dynamic Images by URL

<img width="1511" height="848" alt="Page Regional Trends 2" src="https://github.com/user-attachments/assets/0f5dd5b5-7c94-43bb-abd7-6e1464be5377" />

### 4. Scenario Analysis Page
The Scenario Analysis is an financial simulation model to evaluate KPIs for the following business goal: increase of global market share via implementation of a new discount policy.  

**Data methodology note**:
*Because this portfolio project utilizes a synthetic dataset, it lacks the behavioral patterns and granular transaction history required to statistically calculate a true price elasticity coefficient (the exact relationship between discount depth and demand growth). Consequently, the dashboard is designed as a deterministic simulation tool. It allows stakeholders to manually input their own strategic assumptions or market expectations regarding demand elasticity to instantly visualize the potential financial outcomes.*


>Technical Features Demonstrated: What-If Parameters, DAX, Conditional Formatting, Charts 

<img width="1521" height="853" alt="Page Regional Trends 2" src="https://github.com/user-attachments/assets/4767cdd8-5b79-465d-a188-2cfa5dd959db" />


The core insight reveals that implementing **a new discount policy resulting in a 4% discount depth** (increased from the baseline of 1.68%), which is projected to expand sales volume and **increase demand by 9%** (stakeholders' assumption), will result in a net profit increase only if the company successfully keeps cost-push inflation or **supplier price growth under 2-2.5%**.

As shown in the simulated scenario, allowing cost inflation to escalate to 3.00% triggers a 12.27% jump in COGS (+$196M), completely outpacing the 5.08% expansion in Net Revenue (+$188M) and resulting in a 0.40% drop in Gross Profit.

