*Product Expiry Tracker*
A Python application that helps you track product expiration dates with a clean GUI interface and SQLite database integration.

*Features*
Product Management - Store product information (name, brand, price, expiry date)

Smart Expiry Detection - Automatically identifies expired products

Database Storage - Uses SQLite for reliable data persistence

User-Friendly Interface - Clean Tkinter GUI for easy interaction

*Requirements*
Python 3.x

Tkinter (included with Python)

SQLite3 (included with Python)

Installation & Usage
Clone the repository

bash
git clone <your-repository-url>
cd product-expiry-tracker
Run the application

bash
python main.py
Database Structure
The application creates a SQLite database (product.db) with the following table:

Column	Type	Description
id	INTEGER	Primary key, auto-incrementing
title	TEXT	Product name
brand	TEXT	Brand name
price	INTEGER	Product price
expiredate	TEXT	Expiration date (YYYY-MM-DD)
Sample Data
The application includes these sample products:

Product	Brand	Price	Expiry Date
Milk	Pak	90000	2025-10-01
Pickle	Badr	50000	2026-02-10
Ice cream	Mihan	30000	2024-10-06
Cheese	Roozaneh	60000	2025-11-13
Bread	Senan	80000	2025-03-08
How It Works
Database Setup - Creates the SQLite database and table structure

Data Population - Inserts sample product data

Expiry Check - Compares product dates against current date

GUI Display - Shows expired products in a clean interface

*Customization*
You can easily modify the product list by editing the product_list variable:

python
product_list = [
    {"title": "your_product", "brand": "your_brand", 
     "price": price, "expiredate": date(year, month, day)},
    # Add more products as needed
]
