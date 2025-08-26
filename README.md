# Online Retail Transactions Analysis
## Project Overview
This project analyzes an online retail transactions dataset containing 1,000 records of customer purchases. The analysis includes data cleaning, transformation, and exploration to gain insights into sales patterns and product information.

## Dataset Information
The dataset contains the following columns:
- **InvoiceNo**: Unique identifier for each transaction
- **StockCode**: Product code identifier
- **Description**: Product description/name
- **Quantity**: Number of units purchased
- **InvoiceDate**: Date of the transaction
- **UnitPrice**: Price per unit of the product
- **CustomerID**: Unique identifier for each customer
- **Country**: Country where the purchase was made

## Data Processing Steps

### 1. Data Loading
- Imported pandas library for data manipulation
- Loaded the dataset from 'online_retail_transactions.csv'

### 2. Data Cleaning
- Checked for missing values in all columns
- Removed duplicate rows to ensure data integrity
- Converted the 'InvoiceDate' column to proper datetime format

### 3. Data Transformation
- Created a new column 'TotalPrice' calculated as Quantity × UnitPrice
- This allows for analysis of total transaction values

### 4. Data Exploration
- Identified that there are 10 unique products in the dataset
- Initial exploration shows transactions from various countries including India, Germany, Canada, South Africa, UK, and France

## Key Findings (Initial)
- The dataset contains 1,000 transactions
- There are 10 unique products in the inventory
- Products include: Smartwatch, USB Flash Drive, Tablet, Mouse, Headphones, Smartphone, Monitor, and others

## Next Steps
Further analysis could include:
- Sales trends over time
- Most popular products by quantity or revenue
- Customer purchasing patterns
- Geographic analysis of sales
- Revenue analysis by product category

## Requirements
- Python 3.x
- pandas library

## Usage
Run the Jupyter notebook `onlinereatil project.ipynb` to execute the analysis and see the results.

