
# Basic Sales Summary from SQLite using Python

## Objective
To extract basic sales insights (total quantity sold and revenue) from a simple SQLite database using SQL in Python, and visualize it with a bar chart.

## Tools Used
- Python
- SQLite (`sqlite3`)
- pandas
- matplotlib

## Features
- Creates a `sales` table and inserts sample data.
- Executes SQL query to get product-wise total quantity and revenue.
- Displays the results using `print`.
- Plots a revenue bar chart with `matplotlib`.

## How to Run
1. Make sure Python is installed.
2. Run the script:
   ```bash
   python sales_summary.py
   ```
3. You’ll see printed output and a saved image `sales_chart.png`.

## Output Example
```
   product  total_quantity  total_revenue
0    Apple              13           26.0
1   Banana              13           19.5
2   Orange               9           22.5
```

## Sample Chart
A bar chart showing revenue per product will be displayed and saved as `sales_chart.png`.
