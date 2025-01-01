# Sales-Analysis-using-PowerBI

This project demonstrates the creation of an interactive dashboard using Power BI, based on sales data. The dashboard visualizes key business metrics such as sales by country, average standard cost, sales by product category, and the relationship between order quantity and total discount.

## Overview

This project demonstrates the creation of an interactive dashboard using Power BI, based on sales data. The dashboard visualizes key business metrics such as sales by country, average standard cost, sales by product category, and the relationship between order quantity and total discount.

## Data Loading and Transformation

-   The project starts by loading data from an Excel file into Power BI.
-   Data transformation steps include:
    -   Removing blank items from columns.
    -   Correcting errors in the `OrderDate` column.
    -   Removing the `OrderCount` column as it contains only constant values.
-   All transformations are applied before visualizations are built.

## Visualizations

The dashboard includes the following visualizations:

### 1. Tree Map: Sales by Country
   - A tree map displays sales for all countries in the dataset.
   - The top three countries with the highest sales are highlighted:
        -   **United States** (Blue).
        -   **Canada** (Red).
        -   **France** (Green).
   - This provides a quick overview of sales performance across different countries.
   - The tree map is customized using Power BI's formatting options.

### 2. Gauge Visual: Average Standard Cost
   - A gauge visual displays the average standard cost.
   - The average standard cost is **454.41**.
   - The gauge is colored **blue** and formatted with a title and border for a professional look.

### 3. Funnel Visual: Product Category Sales
   -   A funnel visual shows sales for each product category.
   -   The product with the highest sales is highlighted in **red**:
        -   **Bikes** with sales of **27.89K**.
   -   The product with the lowest sales is:
        -   **Clothing** with sales of **1.26K**.
   -  The visual is formatted with titles, borders, and shadows for improved presentation.

### 4. Line Graph: Order Quantity vs. Total Discount
   - A line graph visualizes the relationship between order quantity and total discount amount.
   - Observations include:
        -   A **positive correlation** when the total discount is between **30K to 70K** with order quantities between **0 and 3** and when the total discount is between **10K to 35K** with order quantities between **10 to 12**.
        -   A **negative correlation** when the total discount is between **30K to 70K** with order quantities between **3 and 10** and when the total discount amount is between **30K to 0K** with order quantities between **12 to 30**.
        -  **No correlation** is observed when the total discount amount is **0K** with order quantities **30 and above**.

## Dashboard Customization

-   All visuals are formatted into a cohesive dashboard.
-   A common color theme and font are used throughout the dashboard for consistency.

## Tools Used

-   Microsoft Power BI
-   Excel

## Conclusion

This project demonstrates how Power BI can be used to transform raw data into meaningful visualizations and insights for business analysis. The interactive dashboard allows for easy exploration of key performance indicators.

Contributions are welcome! Please feel free to open an issue or submit a pull request.

This project is licensed under the MIT License.
```
