#  Depreciation Calculator: Straight-Line vs. Diminishing Balance

##  Project Overview
This project is an automated financial model designed to evaluate and compare two primary methods of asset depreciation: **Straight-Line (SL)** and **Diminishing Balance (DB)**. By inputting baseline asset metrics, the model dynamically generates 10-year depreciation schedules and comparative visualizations. The goal is to provide data-driven recommendations on which accounting method a business should use based on the specific type of asset (e.g., durable goods vs. high-tech infrastructure).

This project was developed as part of the CoachX MITG learning program.

##  Objectives
1. **Automated Financial Modeling:** Build a dynamic Excel engine where changing a single global variable (like Asset Cost) updates all schedules instantly.
2. **Straight-Line Analysis:** Calculate constant, linear depreciation for stable assets.
3. **Diminishing Balance Analysis:** Implement recursive decay formulas to model rapid obsolescence and front-loaded expenses.
4. **Comparative Visualization:** Generate intuitive charts to contrast asset value decay and annual expense distribution.
5. **Business Reporting:** Synthesize mathematical findings into actionable corporate recommendations.

##  Tools & Technologies Used
* **Microsoft Excel:** Financial formulas, absolute referencing, recursive data modeling, and chart generation.
* **Microsoft PowerPoint:** Executive presentation of methodologies and financial insights.

##  Methodology & Workflow

### 1. The Data Model (Input Configuration)
Configured a centralized input table with baseline variables:
* **Total Asset Price:** $500,000 (Cost + Additional setup fees)
* **Scrap (Salvage) Value:** $50,000
* **Estimated Life Span:** 10 Years

### 2. Algorithm Implementation
* **Straight-Line Engine:** Applied `(Asset Price - Scrap Value) / Life Span` to generate a flat $45,000/year expense.
* **Diminishing Balance Engine:** Calculated an exact decay rate (`~20.57%`) and applied it recursively to the remaining book value year-over-year.

### 3. Data Visualization
Built comparative dashboards to illustrate the mathematical differences:
* **Asset Value Decay (Line Chart):** Visualizes the linear 45-degree drop of SL against the steep, exponential curve of DB.
* **Expense Comparison (Column Chart):** Highlights how the DB method front-loads financial expenses in the early years.

