# Sales and Inventory Analysis - Tableau Story

## Project Overview
This project focuses on analyzing e-commerce data to optimize customer relationship management and regional logistics. By integrating data from multiple tables , I developed an interactive Tableau Story to help stakeholders identify high-value customers and visualize geographical revenue distribution.

<img width="1753" height="380" alt="Screenshot (182)" src="https://github.com/user-attachments/assets/f5d6ed80-92cc-4939-9eb2-535ebac68d8d" />

## Executive Summary & Key Insights
Through the development of this analysis, the following business questions were addressed:

* **Top Performing Customer:** **Berniece Blakely** was identified as the customer from the West region who placed the order with the highest price.
* **West and South regions** led in terms of Revenue and Customer Acquisition.
* **Waterbury and Santa Barbara** had the highest amount of delivery charges.
* **Highest Revenue State:** In the North East region, **Connecticut** emerged as the state generating the highest total revenue.
* **Revenue Calculation:** A custom calculated field was created to determine total revenue:  
    `Revenue = ([Order Price] * [Unit]) + [Delivery Charge]`

## Detailed Project Workflow

### Dashboard 1: Customer Analysis
**Goal:** Identify high-value customers and understand purchasing patterns.
* **Top N Customers:** A dynamic view using a **Parameter** (Top 1–10) to filter the highest-spending customers by `Order Price`.
* **Customer Acquisition:** A stacked bar chart showing the count of unique customers across different regions, segmented by year.
* **Order Frequency:** A bar chart to visualize how many customers purchase specific quantities.
* **Interactive Features:** Implemented a **Filter Action** on the "Top N Customers" sheet to update the acquisition and frequency charts simultaneously.

### Dashboard 2: Geographical Performance
**Goal:** Visualize revenue distribution and logistics costs across the United States.
* **Revenue by Region:** A bar chart showing revenue of each region.
* **Revenue by State:** A geographical map to highlight high-performing states.
* **Delivery Charges per City:** A sorted bar chart identifying cities with the highest delivery overhead.
* **Interactive Features:**
    * **Filter Action:** Selecting a Region filters the State and City views.
    * **URL Action:** Selecting a state triggers a **Wikipedia URL Action** that opens the specific state's page within a **Web Page Object** on the dashboard.

## Technical Skills Demonstrated
* **Data Modeling:** Connecting and joining different tables in Tableau.
* **Calculated Fields:** Creating complex formulas for revenue and logistics metrics.
* **Parameters & bins:** Enhancing user interactivity and data segmentation.
* **Advanced Interactivity:** Implementing Filter and URL actions for deep-dive analysis.
* **Data Storytelling:** Compiling dashboards into a cohesive "Sales and Inventory Story".

# Final Dashboards
<img width="1601" height="801" alt="Screenshot (124)" src="https://github.com/user-attachments/assets/5d7dda08-6dd9-479b-b33a-7abeacbdfa98" />
<img width="1608" height="806" alt="Screenshot (125)" src="https://github.com/user-attachments/assets/5df4512f-1912-4790-9cc9-72a2f6a3247a" />

# Link to the Tableau Story on Tableau Public
https://public.tableau.com/views/Tableau_Sales_And_Inventory_Story/SalesAndInventoryStory?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

*Developed as part of a Data Analytics Portfolio.*

