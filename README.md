# Bookstore Management & Sales Analysis System

## Project Overview

The **Bookstore Management & Sales Analysis System** is a Python-based project that manages bookstore inventory and sales data.

The project uses **Pandas** for data handling, **NumPy** for numerical analysis, **Matplotlib** and **Seaborn** for data visualization, and **OOP (Object-Oriented Programming)** to organize the bookstore operations.

The system provides a menu-driven interface for managing books, recording sales, generating reports, performing analysis, and creating visualizations.

## Technologies Used

- **Python**
- **Pandas** – DataFrame operations, data cleaning, merging, grouping, and CSV handling
- **NumPy** – Numerical calculations and array-based analysis
- **Matplotlib** – Bar chart, line graph, and pie chart
- **Seaborn** – Heatmap visualization
- **Jupyter Notebook** – Development and execution environment

## Files

```text
Bookstore-Project/
│
├── Bookstore.ipynb
├── inventory.csv
├── sales.csv
└── README.md
```

## Dataset

### inventory.csv

The inventory dataset contains information about books, including:

- Title
- Author
- Genre
- Price
- Quantity

### sales.csv

The sales dataset contains information about book sales, including:

- Date
- Title
- Quantity Sold
- Total Revenue

## Main Features

### 1. Add Book
Adds a new book to the inventory.

The system checks:
- Price must be greater than 0
- Quantity cannot be negative
- Title cannot be empty
- Duplicate books are not allowed

### 2. Remove Book
Removes a book from the inventory using its title.

### 3. Update Inventory
Updates the available quantity of an existing book.

### 4. Record Sale
Records a book sale and automatically:
- Checks whether the book exists
- Checks available stock
- Calculates revenue
- Updates inventory quantity
- Adds the sale to the sales DataFrame

### 5. Show Inventory
Displays the current bookstore inventory.

### 6. Show Sales
Displays the sales records.

### 7. Generate Report
Generates a summary containing:

- Total book titles
- Total stock
- Total books sold
- Total revenue
- Average book price
- Best-selling book
- Number of books sold for the best-selling book

### 8. NumPy Analysis
Uses NumPy functions to calculate:

- Average book price
- Total books sold
- Average books sold
- Total revenue

### 9. Sales by Genre
Groups sales according to genre and displays the quantity sold for each genre.

### 10. Sales by Author
Groups sales according to author and displays the quantity sold for each author.

### 11. Best Selling Books
Finds and sorts books according to the total quantity sold.

### 12. Revenue by Genre
Calculates total revenue for each genre.

## Data Visualizations

The project includes four visualizations:

### Bar Chart
Shows the quantity of books sold by genre.

### Line Graph
Shows the monthly sales/revenue trend.

### Pie Chart
Shows the revenue share of each genre.

### Heatmap
Shows the correlation between book price and quantity sold.

## OOP Implementation

The project uses a `Bookstore` class.

The class stores:

- `inventory` – bookstore inventory DataFrame
- `sales` – sales DataFrame

The main methods include:

- `add_book()`
- `remove_book()`
- `update_inventory()`
- `record_sale()`
- `generate_report()`
- `numpy_analysis()`
- `sales_by_genre()`
- `sales_by_author()`
- `best_selling_books()`
- `revenue_by_genre()`
- `bar_chart()`
- `line_graph()`
- `pie_chart()`
- `heatmap()`
- `show_inventory()`
- `show_sales()`

## Data Processing

Before running the bookstore system, the project:

- Loads CSV files using Pandas
- Checks for missing values
- Removes duplicate records
- Converts the sales `Date` column to datetime format

## How to Run

1. Install Python.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Keep these files in the same folder:

```text
Bookstore.ipynb
inventory.csv
sales.csv
```

4. Open the notebook in Jupyter Notebook or VS Code.
5. Run the notebook cells.
6. Run the menu and select an option from `1` to `17`.

## Menu

```text
========== BOOKSTORE SYSTEM ==========

1. Add Book
2. Remove Book
3. Update Inventory
4. Record Sale
5. Show Inventory
6. Show Sales
7. Generate Report
8. NumPy Analysis
9. Sales by Genre
10. Sales by Author
11. Best Selling Books
12. Revenue by Genre
13. Bar Chart
14. Line Graph
15. Pie Chart
16. Heatmap
17. Exit
```

## Concepts Demonstrated

This project demonstrates practical use of:

- Object-Oriented Programming
- Classes and objects
- Constructor (`__init__`)
- Pandas DataFrames
- CSV file handling
- Data cleaning
- Filtering
- `loc`
- `groupby()`
- `merge()`
- `concat()`
- Sorting
- NumPy calculations
- Matplotlib visualization
- Seaborn visualization
- Input validation
- Menu-driven programming

## Author
Nirpalsinh Solanki

