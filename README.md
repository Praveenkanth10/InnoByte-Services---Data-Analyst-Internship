Amazon Sales Report Analysis

## Project Overview

This project analyzes Amazon sales data to gain insights into sales trends, customer behavior, and product performance. It leverages data visualization to present these insights in an understandable manner.

## Data Source

The dataset used for this analysis is "Amazon Sale Report ". It contains information about sales transactions on Amazon, including order ID, date, status, fulfillment method, sales channel, product category, size, quantity, amount, shipping details, and more.

## Analysis Steps

1. **Data Loading and Cleaning:**
   - Load the sales data from the CSV file into a pandas DataFrame.
   - Perform initial data exploration using `head()`, `describe()`, and `info()`.
   - Handle missing values using `isnull().sum()` and `dropna()`.
   - Select relevant columns for further analysis.

2. **Exploratory Data Analysis (EDA):**
   - Investigate the distribution of key variables like 'Size', 'Status', 'ship-city', and 'Category' using `value_counts()`.
   - Understand the frequency and patterns of different order attributes.

3. **Data Visualization:**
   - Create bar charts to show the demand for different sizes, order status distribution, and top cities with the most orders.
   - Use a line plot to illustrate the sales trend over time based on the order date and amount.

4. **Sales Overview:**
   - Convert the 'Date' column to datetime objects.
   - Group sales data by date and calculate total sales per day.
   - Create a line plot to visualize the sales trend over time.

## Insights and Potential Applications

- **Demand Analysis:** Identify popular product sizes, categories, and customer locations.
- **Sales Performance:** Track sales trends over time to understand growth patterns and potential seasonal effects.
- **Order Fulfillment:** Analyze order status to gain insights into the efficiency of order processing and shipping.
- **Business Decisions:** Use the insights to optimize inventory, marketing strategies, and logistics operations.

## Dependencies

- Python 3
- pandas
- matplotlib
- seaborn
- numpy

## Usage

1. Clone this repository.
2. Install the required dependencies.
3. Run the Jupyter Notebook `Amazon_Sales_Analysis.ipynb`.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
