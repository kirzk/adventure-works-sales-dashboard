# Adventure Works Sales and Profit: Data Visualization Case Study

Final case study for **Data 035: Data Storytelling and Visualization** at the Southern Alberta Institute of Technology (SAIT).

**Live dashboard:** *(add your GitHub Pages link here after you turn Pages on)*

## Group project and my part

This was a group project with **Marissa**. I built the three Goal 1 Tableau charts: sales and profit by category and subcategory, top and bottom selling product models, and the sales and profit trend over time. Marissa built the three Goal 2 charts: sales by country, by occupation and by annual income range. The original Tableau workbook in this repository contains my Goal 1 charts.

The interactive web page in this repository shows all six charts. I rebuilt it afterwards from the same data so the whole case study can be viewed in one place.

## Business problem

The audience is the VP of Sales, the VP of Marketing and the VP of Product. The case study answers six questions in two goals.

**Goal 1: examine products and their sales and profit**
1. What are the sales and profits by category and subcategory?
2. What are the top and bottom selling products?
3. What are the sales and profit trends?

**Goal 2: examine sales and customer demographics**
1. What are the sales by country?
2. What are the sales by occupation?
3. What are the sales by income range?

## Data

The Adventure Works sample dataset (sales, customers, products, categories, subcategories and territories), covering January 2020 to early December 2022. About 56,000 order lines.

- Sales = order quantity × product price
- Profit = order quantity × (product price − product cost)

## Key findings

- Total sales are about **$24.9M** and profit about **$10.5M**, a margin of about **42%**.
- **Bikes make up about 95% of sales.** Road Bikes ($11.3M), Mountain Bikes ($8.6M) and Touring Bikes ($3.8M) are the largest subcategories.
- The **United States** ($7.9M) and **Australia** ($7.4M) are the largest markets.
- The **$50-70K income range buys the most** (about 29% of sales). More income does not mean more purchases.
- **Professionals** are the largest occupation group ($8.5M).
- Sales fall about **75% from June to July 2022** and stay low until the data ends. The dataset does not explain why. The data may be incomplete for the later months, so this should be checked before treating it as a real decline.

## What is in this repository

| Path | What it is |
| --- | --- |
| `index.html` | The interactive dashboard (open it in a browser, or view it with GitHub Pages) |
| `data/` | The six small summary tables the dashboard is drawn from (CSV) |
| `tableau/Final Case Study.twb` | The original Tableau workbook (Goal 1 charts). It needs `Advanture Dataset.xlsx` from the course to open. |

## Tools

- Tableau Desktop: the original charts and analysis
- HTML and D3.js: the interactive web version of the same charts. I rebuilt it from the same data with help from Claude (an AI assistant) so it can be shared as a web page.

## Author

Kyrylo Tsyrulik
