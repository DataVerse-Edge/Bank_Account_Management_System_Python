# Bank_Account_Management_System_Python
# Bank Account Management System

A console-based Python project that simulates basic banking operations such as account creation, deposits, withdrawals, fund transfers, and transaction history management. This project is designed to demonstrate core Python concepts including variables, functions, object-oriented programming, file handling, exception handling, and the use of external libraries like NumPy.

## Description

The Bank Account Management System allows users to create and manage bank accounts through an interactive menu-driven interface. Each account includes details such as account holder name, auto-generated account number, account type, and current balance.

The system supports essential banking transactions including deposit, withdrawal, and transfer between accounts. It also stores account details and transaction history using the `pickle` module, so data can be saved and loaded between program runs.

In addition, the project provides transaction history reports for each account, showing the date, transaction type, and amount. Summary statistics such as total deposits, total withdrawals, and average transaction amount are calculated using NumPy.

This project was built as a practical learning exercise to apply important Python programming concepts in a real-world style mini project.

## Features

- Open a new bank account
- View account details
- Deposit money
- Withdraw money
- Transfer money between accounts
- View transaction history
- Save and load data using pickle
- Generate summary statistics using NumPy
- Input validation and error handling
- Bonus login system with username and password

## Technologies Used

- Python
- NumPy
- Pickle
- OOP (Classes and Objects)
- File Handling
- Exception Handling

## How It Works

When the program starts, it loads saved account and transaction data from pickle files. Users can then choose actions from the menu, such as creating an account or performing a transaction. Each transaction updates the account balance and is stored in the transaction history. When the program exits, all updated data is saved back to the files.

## Purpose

The main purpose of this project is to practice Python fundamentals by building a simple real-world banking simulation. It is suitable for beginners who want to understand how Python concepts work together in one project.

## Future Improvements

- Add a graphical user interface (GUI)
- Improve password security and user authentication
- Add account deletion and update options
- Export transaction reports to text or CSV files
- Connect the system to a database instead of pickle files
