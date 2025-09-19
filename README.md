Product Receipt Program

This Python program manages a list of products, stores them in an SQLite database, and displays expired products in a simple GUI using Tkinter.

Features

Stores product information (title, brand, price, expiration date) in SQLite.

Checks for expired products automatically.

Displays expired products in a Tkinter window.

Uses a clean and simple GUI interface.

Requirements

Python 3.x

Tkinter (usually included with Python)

sqlite3 (built-in with Python)

Setup and Usage

Clone or download the project.

Run the product_table() function to create the database and insert the initial products:

product_table()


Run the show_expired() function to display expired products in the GUI:

show_expired()


The Tkinter window will open:

If there are expired products, they will be listed with their title.

If no products are expired, it will show a “No expired products” message.

Database Details

Database file: product.db

Table: product

Columns:

id (INTEGER PRIMARY KEY AUTOINCREMENT)

title (TEXT)

brand (TEXT)

price (INTEGER)

expiredate (TEXT, stored in YYYY-MM-DD format)

Notes

Expiration dates are stored as text in ISO format (YYYY-MM-DD) for compatibility with SQLite date functions.

The GUI is minimal and uses Tkinter’s Label widget with place() for positioning.

Example Product List
Title	Brand	Price	Expire Date
milk	pak	90000	2025-10-01
pickle	badr	50000	2026-02-10
ice cream	mihan	30000	2024-10-06
cheese	roozaneh	60000	2025-11-13
bread	senan	80000	2025-03-08
