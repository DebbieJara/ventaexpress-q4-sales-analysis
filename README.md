# ventaexpress-q4-sales-analysis

![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat&logo=google-sheets&logoColor=white)

**Business question:** What Q4 2024 sales patterns can inform the January 2025 commercial strategy?

## Context

VentaExpress is an e-commerce company selling technology products (laptops, phones, headphones, tablets) in Mexico and Colombia. October-December 2024 sales data was analyzed as delivered, unprocessed (inconsistent formatting, duplicate and missing values, disorganized columns).

## Process

1. **Cleaning:** identified and corrected mis-encoded special characters, empty cells (12 in Unit Price, 7 in Total Amount), column formatting (currency symbol, data types), and one invalid date (16/16/2024), removed since the date (16/16/2024) doesn't exist on the calendar.
2. **Analysis:** calculated metrics by product, city, category, and month.
3. **Visualization:** built executive charts to communicate findings.

## Key findings

- Best-selling product by quantity: Laptop-Oficina-32GB
- City with highest sales volume: Mexico City
- Average price by category: Headphones $1,253.74 · Laptop $1,305.42 · Tablet $1,261.51 · Phone $1,281.17
- Sales grow sharply starting in September, peaking at \~$1.07M in October. November holds nearly the same level (-1.4%), but December shows a sharper drop of 8.9% (\~$94K less than November).
- Tulum shows notably lower sales volume than the other cities, though the dataset doesn't specify whether this reflects a recent market entry or another factor.

## Visualizations

![Total sales by city and monthly sales evolution](images/q4-sales-charts.png)

Total sales by city (Mexico City leads, followed by Cali and Monterrey) and monthly sales evolution, showing the sharp Q4 spike and December's decline.

## Recommendation

Analyze the marketing strategies used in October-November to replicate them in January and slow the downward trend that started in December.

## Limitations

Deepening this analysis would require actual marketing campaign execution data, plus a profitability calculation (not just revenue) to confirm that cities like Mexico City and Cali generate healthy margin, not just cash flow.

## Tools

Google Sheets (cleaning, analysis, visualization)

## Dataset

Full dataset: [View in Google Sheets](https://docs.google.com/spreadsheets/d/1qVelKsjQykPKQqOiyyu1A5sLLQGvSSKn/edit?usp=sharing&ouid=106602298566061042272&rtpof=true&sd=true)

---

By Deborah Jara | Business Intelligence · Data Analytics | Mexico
[LinkedIn](https://www.linkedin.com/in/deborahjara) · [GitHub](https://github.com/DebbieJara)
