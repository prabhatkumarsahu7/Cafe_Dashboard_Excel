# Cafe_Dashboard_Excel

# Cafe Sales Dashboard Project

## Overview
This repository contains an Excel dashboard designed for a café to analyze key sales metrics. The dashboard offers insights into total revenue, footfall, product sales, and customer behavior. It is an interactive tool aimed at providing the café management team with a clear view of sales performance and trends.

## Project Purpose
The goal of this project is to:
- Visualize café sales data in a user-friendly and interactive manner.
- Provide insights on customer preferences, product performance, and store operations.
- Facilitate decision-making for café management by identifying high-performing products and peak sales hours.

## Dashboard Features

### 1. Key Performance Indicators (KPIs)
- Total revenue generated across all store locations.
- Average bill per person.
- Total footfall and quantity sold.

### 2. Sales and Footfall Trends
- **Day-wise and Hour-wise Trends**: Visualizations that show the café's busiest days and hours.
- **Store Comparison**: Displays footfall and sales across different store locations (e.g., Astoria, Hell’s Kitchen, Lower Manhattan).

### 3. Top Products by Sales
Highlights the top 5 products based on sales, such as Barista Espresso, Brewed Black Tea, and Hot Chocolate.

### 4. Product Size and Category Breakdown
- A pie chart showing order sizes (Large, Regular, Small).
- Sales breakdown across various product categories like coffee, bakery, tea, and more.

### 5. Hourly Order Distribution
Line chart that visualizes the number of products ordered throughout the day, helping to identify peak sales hours.

## Dataset
The dataset consists of transaction records from multiple store locations with the following fields:

| Column Name       | Description                                             |
|-------------------|---------------------------------------------------------|
| `transaction_id`   | Unique identifier for each transaction.                |
| `transaction_date` | Date of the transaction (dd-mm-yyyy format).           |
| `transaction_time` | Time of the transaction.                               |
| `store_id`         | Unique identifier for the store.                       |
| `store_location`   | Name of the store location (e.g., Astoria, Manhattan). |
| `product_id`       | Unique identifier for the product sold.                |
| `transaction_qty`  | Quantity of products sold in the transaction.          |
| `unit_price`       | Price per unit of the product.                         |
| `product_category` | The category of the product (e.g., Coffee, Tea).       |
| `product_type`     | The type of the product (e.g., Brewed Tea, Bakery).    |
| `product_detail`   | Specific details of the product (e.g., Peppermint).    |
| `size`             | Size of the product ordered (e.g., Large, Regular).    |
| `total_bill`       | Total amount billed for the transaction.               |
| `month_name`       | The month of the transaction (e.g., June, July).       |
| `day_name`         | The day of the week (e.g., Monday, Tuesday).           |
| `hour`             | The hour of the day when the transaction occurred.     |
| `day_of_week`      | Numeric value for the day of the week (1-7).           |
| `month`            | Numeric value for the month (1-12).                    |

## Tools Used
1. **Microsoft Excel**:
   - Pivot Tables for data summarization.
   - Charts (Bar, Pie, Line) to visualize trends and distributions.
   - Conditional Formatting for dynamic highlighting of key metrics.
   - Slicers for interactive filtering based on day, month, and store location.

2. **Design Techniques**:
   - Consistent color schemes, gradients, and shading to enhance visual appeal.
   - User-friendly layout for easier navigation of the dashboard.

## Usage Instructions

1. **Download the Dashboard**:
   - Download the Excel file from this repository: [Cafe_Sales_Dashboard.xlsx](link_to_excel_file).

2. **Explore Interactive Features**:
   - Use the slicers to filter the data by day, month, and store location.
   - Analyze sales trends, top-performing products, and footfall at different times of the day.

3. **Modify and Adapt**:
   - You can adapt this dashboard to your own dataset by replacing the existing data and updating the pivot tables accordingly.

## Screenshots
### 1. Overall Dashboard View
![Dashboard](link_to_screenshot)

### 2. Top Products and Sales Distribution
![Sales Distribution](link_to_screenshot_2)

## Future Enhancements
- Integrating advanced analytics such as customer segmentation and product inventory analysis.
- Creating an automated report generation system.
- Expanding the project to include web-based dashboards (e.g., Power BI or Tableau).

## License
This project is licensed under the MIT License - see the [LICENSE](link_to_license) file for details.

## Contributing
Contributions are welcome! If you have suggestions for improvements or find any bugs, feel free to create an issue or submit a pull request.

