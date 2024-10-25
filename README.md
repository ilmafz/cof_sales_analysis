# cof_sales_analysis

# Project Overview
This project analyzes a dataset containing coffee sales from a vending machine. The dataset includes sales data recorded over several months, with details on each sale such as date, time, payment type, amount spent, and coffee product. The goal of this analysis is to gain insights into customer behavior and identify trends in coffee sales over time.

# Dataset Description
**Rows** : 1133 entries
**Columns** : 
  - `date`: Sale date
  - `datetime`: Sale timestamp
  - `cash_type`: Payment method
  - `card`: Card ID
  - `money`: Amount Spent
  - `coffee_name`: Type of Coffee purchased

# Objective
1. **Data Cleaning**:
   - Handle missing values.
   - Convert date and time columns to datetime format.
   - Check for duplicates.
   - 
3. **Exploratory Data Analysis (EDA)**:
   - Generate insights on sales patterns by time, day, and product type.
   - 
5. **Sales Trends Analysis**:
   - Hourly, daily, and monthly sales trends.
   - Weekly sales distribution.
   - Popularity of different coffee products.
   - 
6. **Visualization**:
   - Use visualizations to illustrate trends, such as sales by hour, product popularity, and   
     sales over time.

# Key Findings
- **Hourly Sales Distribution**: Shows sales trends by hour to identify peak times.
- **Daily Sales Line Plot**: Illustrates total sales over days.
- **Weekly Sales Bar Plot**: Sales trends for each day of the week.
- **Monthly Sales Bar Plot**: Total sales by month to spot seasonality.
- **Hourly Sales Bar Plot For Each Coffee**: Identifies peak sales times for different coffee types.
- **Product Popularity Chart**: Coffee preferences among customers.

# Usage
1. **Prerequisites**:
   -Python: Version 3.11.5
   -Required Libararies:
     - pnadas
     - numpy
     - matplotlib
     - seaborn
     - datetime
     - 
2. **Running the Analysis**:
     - Clone the repository:
       ```bash
       git clone https://github.com/ilmafz/cof_sales_analysis.git
       ```
     - Navigate to the project Directory:
       ```bash
       cd cof_sales_analysis
       ```
     - Install the necessary packages:
       ```bash
       pip install -r requirements.txt
       ```
  
# Project Files
- `cof_sales.csv`: Raw dataset with coffee sales records.
- `project cof_sales.ipynb`: Jupyter Notebook containing data cleaning, EDA, and visualizations.
- `README.md`: Project overview and documentation.

# Acknowledgments
This project was developed by [Ilma Fatma Zaidi](https://github.com/ilmafz), as a personal project to explore sales trends and develop data analysis skills.

  
     

