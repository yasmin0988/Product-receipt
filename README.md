Product Receipt Program

A simple Python program that manages products, stores them in an SQLite database, and displays expired products in a GUI using Tkinter.

Features

Store product information (title, brand, price, expiration date) in SQLite.

Automatically check for expired products.

Display expired products in a clean and simple GUI.

Requirements

Python 3.x

Tkinter (usually included with Python)

SQLite3 (built-in with Python)

Setup

Clone the repository:

git clone <your-repo-url>
cd <your-repo-folder>


Create the product database and insert initial products:

from your_script_name import product_table
product_table()


Display expired products in the GUI:

from your_script_name import show_expired
show_expired()

Database Details

Database file: product.db

Table: product

Columns:

id — INTEGER PRIMARY KEY AUTOINCREMENT

title — TEXT

brand — TEXT

price — INTEGER

expiredate — TEXT (YYYY-MM-DD)

Note: Expiration dates are stored as text in ISO format (YYYY-MM-DD) for compatibility with SQLite’s date functions.

Example Product List
Title	Brand	Price	Expire Date
milk	pak	90000	2025-10-01
pickle	badr	50000	2026-02-10
ice cream	mihan	30000	2024-10-06
cheese	roozaneh	60000	2025-11-13
bread	senan	80000	2025-03-08
Notes

The GUI is minimal, using Tkinter Label widgets with place() for positioning.

Expired products are shown automatically when the GUI opens.

Python’s datetime is used to check expiration dates.
Title	Brand	Price	Expire Date
milk	pak	90000	2025-10-01
pickle	badr	50000	2026-02-10
ice cream	mihan	30000	2024-10-06
cheese	roozaneh	60000	2025-11-13
bread	senan	80000	2025-03-08
