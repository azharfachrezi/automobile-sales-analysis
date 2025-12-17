# Automobile Sales Analytics Dashboard 🚗

## Overview
This project is an interactive data visualization dashboard designed to analyze historical automobile sales data. It focuses on comparing sales trends between **Recession** and **Non-Recession** periods to derive actionable business insights.

The dashboard allows users to filter data by year and view various metrics such as average sales, advertising expenditure, and vehicle type distribution.

## Tech Stack
* **Python:** Core programming language.
* **Dash & Dash Mantine Components:** For the responsive web interface.
* **Pandas:** For data manipulation and aggregation.
* **Plotly Express:** For generating interactive charts.

## Key Features
* **Recession Analysis:** Compare sales volume and GDP impact during recession periods (e.g., 1980, 2008).
* **Interactive Filters:** Toggle between "Yearly Statistics" and "Recession Period Statistics."
* **Visualizations:**
    * Line charts for yearly automobile sales.
    * Pie charts showing advertising expenditure by vehicle type.
    * Bar charts for average sales per vehicle type.

## How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/azharfachrezi/automobile-sales-analysis.git](https://github.com/azharfachrezi/automobile-sales-analysis.git)
    ```
2.  Install the required libraries:
    ```bash
    pip install pandas dash dash-mantine-components plotly
    ```
3.  Open the file **`Automobile_Sales_Dashboard (Mantine).ipynb`** in Jupyter Notebook or VS Code.
4.  Run all cells to launch the dashboard locally.

## Project Structure
* `Automobile_Sales_Dashboard (Mantine).ipynb`: The main dashboard file using the modern Mantine UI.
* `Automobile_Sales_Dashboard (bootstrap).ipynb`: An alternative version using Bootstrap.
* `Automobile_Sales_Dashboard.ipynb`: The initial development notebook.
