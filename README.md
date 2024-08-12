# Sales Data Analysis

This project involves analyzing sales data to derive insights and visualize trends using Python. The provided code demonstrates how to:

1. **Load and Explore Data**: Read a CSV file containing sales data and perform initial exploration.
2. **Clean and Process Data**: Handle missing values and convert date columns to datetime format.
3. **Perform Analysis**: Calculate total revenue by product category and average profit by age group.
4. **Visualize Data**: Create bar charts to visually represent the results of the analysis.

## Prerequisites

Before running the code, make sure to install the necessary Python libraries. You can install them using pip:

```bash
pip install pandas numpy matplotlib fpdf
```

## Code Description

1. **Import Libraries**:
   - `pandas` for data manipulation.
   - `numpy` for numerical operations.
   - `matplotlib.pyplot` for data visualization.

2. **Load the Data**:
   - Reads the CSV file located at `file_path` into a DataFrame.
   - Displays the first few rows, summary, and statistical summary of the dataset.

3. **Data Cleaning**:
   - Checks for and displays missing values in the dataset.
   - Converts the 'Date' column to datetime format.

4. **Analysis**:
   - **Total Revenue by Product Category**: Groups data by 'Product_Category' and calculates the total revenue for each category.
   - **Average Profit by Age Group**: Groups data by 'Age_Group' and calculates the average profit for each age group.

5. **Visualization**:
   - **Total Revenue by Product Category**: Plots a bar chart showing total revenue for each product category.
   - **Average Profit by Age Group**: Plots a bar chart showing average profit for each age group.

## How to Use

1. Place your `sales_data.csv` file in the same directory as this script or update the `file_path` variable with the correct path to your CSV file.
2. Run the script to perform data loading, cleaning, analysis, and visualization.

## Example Output

- The script will output the first few rows, summary, and statistical summary of the dataset.
- It will also print the total revenue by product category and the average profit by age group.
- Two bar charts will be displayed: one for total revenue by product category and one for average profit by age group.

## Notes

- Ensure that your CSV file contains the columns: 'Date', 'Product_Category', 'Revenue', 'Age_Group', and 'Profit'.
- Adjust the column names in the script if they differ in your dataset.
