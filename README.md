# Expense-Tracker
Task 02 — Expense Tracker

About the Project

The Expense Tracker is a simple Python program that helps users record their daily expenses. It stores the date, category, and amount of each expense and saves the data in a CSV file.

Features

- Add multiple expenses.
- Validate the date and amount before accepting an expense.
- Store each expense as a dictionary.
- Calculate spending for each category.
- Calculate total spending.
- Save expenses to a CSV file that can be opened in a spreadsheet.

Technologies Used

- Python 3
- CSV module
- Datetime module

How to Run

1. Save the code as "expense_tracker.py".
2. Open a terminal in the project folder.
3. Run "python expense_tracker.py".
4. Enter the requested expense details.
5. Open "expenses.csv" to view the saved records.

Decisions Made

- Dates must follow the YYYY-MM-DD format.
- Expense amounts must be valid numbers greater than zero.
- Categories cannot be empty.
- The program creates a new CSV file each time it saves.

What I Learned

This project helped me practice Python dictionaries, lists, functions, loops, input validation, and CSV file handling.

Conclusion

The project provides a simple way to record and analyze expenses while keeping the data organized in a spreadsheet-friendly format.
