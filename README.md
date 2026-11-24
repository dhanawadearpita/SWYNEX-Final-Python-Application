# SWYNEX Smart Expense Tracker

A modular, command-line Python application for recording income and expenses, reviewing transactions, searching by category, and viewing a financial summary. Built as a final Python application project for internship learning.


## Features
- Record income or expense transactions with date, category, amount, and description
- View all saved transactions
- Calculate total income, total expenses, and balance
- Search transactions by category (partial match supported)
- Input validation and friendly error handling
- Persistent storage using CSV
- Modular design separating validation, storage, and application logic

## Requirements
- Python 3.8 or newer
- No third-party packages are needed (Python standard library only)

## Setup and run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/SWYNEX-Final-Python-Application.git
   cd SWYNEX-Final-Python-Application
   ```
2. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv venv
   # Windows PowerShell:
   .\venv\Scripts\Activate.ps1
   # Windows Command Prompt:
   venv\Scripts\activate.bat
   # macOS/Linux:
   source venv/bin/activate
   ```
3. Run the app:
   ```bash
   python main.py
   ```
## Usage
Choose an option from the menu. When adding a transaction, use `income` or `expense`, enter a positive amount, and use a date in `YYYY-MM-DD` format (or leave the date blank to use today's date). Transactions are saved in `data/transactions.csv`.


## Project structure
```text
SWYNEX-Final-Python-Application/
├── main.py
├── requirements.txt
├── README.md
├── .gitignore
├── app/
│   ├── __init__.py
│   ├── tracker.py
│   ├── storage.py
│   └── validators.py
├── data/
│   └── transactions.csv
└── tests/
```

## Concepts demonstrated
Functions, modules, CSV file handling, validation, exception handling, loops, conditional logic, and basic financial calculations.

## Author
Arpita Dhanawade
