Product Expiry Tracker
A Python application that tracks product expiry dates with a GUI interface and SQLite database.

Features
Tracks product information (name, brand, price, expiry date)

Identifies expired products

SQLite database storage

Simple Tkinter GUI

Requirements
Python 3.x

Tkinter

SQLite3

Usage
Run the script to:

Create a SQLite database with product table

Populate with sample data

Display expired products in a GUI window

The application checks products against the current date and shows any that have expired.

Database
Creates a SQLite database (product.db) with a table containing:

Product name, brand, price, and expiry date

Sample products include milk, pickle, ice cream, cheese, and bread with various expiry dates.
Title	Brand	Price	Expire Date
milk	pak	90000	2025-10-01
pickle	badr	50000	2026-02-10
ice cream	mihan	30000	2024-10-06
cheese	roozaneh	60000	2025-11-13
bread	senan	80000	2025-03-08
