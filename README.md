# Madhav_E-Commerce-_Sales_dashboard

Overview

An interactive Power BI dashboard analyzing end‑to‑end e‑commerce performance, including revenue, quantity, profit, and average order value, with drill‑downs by state, customer, category, payment mode, and sub‑category.
Designed for weekly business reviews with slicers for quarter and segment to answer “where is profit coming from and why,” and “which levers will improve margin next.”

File structure:-
data/: raw or cleaned CSV/Excel files used in the model.
pbix/: Madhav_Ecommerce_Sales_Dashboard.pbix (report + model).
images/: dashboard screenshots, including Madhav-E-commerce.jpg.


KPIs:-
Sum of Amount: 438K — total revenue across selected period and filters.
Sum of Quantity: 5615 — total units sold across all orders.
Sum of Profit: 37K — gross profit after cost-of-goods.
AOV: 121K — average order value derived as Revenue ÷ Orders; shown for quick margin context.

Report pages and visuals-
Profit by Month: column chart to spot seasonal swings and month-over-month changes.
Amount by State: bar chart highlighting contribution and white‑space in top states (e.g., Maharashtra, MP, UP).
Quantity by Category: donut chart to compare category mix (Clothing, Electronics, Furniture).
Amount by Customer: top customers bar to drive account‑level actions.
Quantity by Payment Mode: share by COD, UPI, debit, credit to optimize checkout mix.
Profit by Sub‑Category: bar chart to identify profitable product niches (e.g., Printers, Bookcases).

Business insights:-
Seasonal pattern: Profit peaks in late Q4 with noticeable dips mid‑year; plan promos and inventory ahead of high months.
Regional concentration: Revenue is disproportionately driven by a few states; expansion and localized campaigns can lift under‑penetrated regions.
Product strategy: Sub‑categories like Printers and Bookcases deliver outsized profit; prioritize assortment depth and attach bundles around these lines.
Category mix: Clothing contributes majority of unit volume while Electronics/Furniture balance ticket size; use cross‑sell to raise basket value.

Payments mix:
COD holds the largest share; shifting share to UPI/cards can reduce returns and logistics cost.
Customer focus: A small set of customers drive a large share of revenue; introduce targeted retention offers and priority service.

Data model and DAX:-
Star schema with fact table for sales and dimensions for date, customer, product, state, and payment mode.
Key measures: Revenue, Quantity, Profit, AOV, Contribution %, MoM/YoY growth, and Profitability by sub‑category.

Contact
Akash Maurya 
Linkedin-https://www.linkedin.com/in/akashrkrmaurya/
email-mauryaakash681@gmail.com
