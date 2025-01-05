# personal-expense-tracker

Personal Expense Tracker

This is a simple console-based Personal Expense Tracker application developed by Dabbiru Sreeraj. The program allows users to track and manage personal expenses by adding, viewing, and summarizing them based on categories. It is provided as a precompiled executable (.exe), so you can use it without needing to compile the source code.

Features
- Add Expense: Add an expense with details like date, category, and amount.
- View All Expenses: Display all recorded expenses.
- View Summary by Category: Get a breakdown of expenses categorized by Food, Travel, Entertainment, Healthcare, Utilities, Shopping, and Miscellaneous.
- Simple User Interface: A console-based interface for easy use.

Installation
1. Download the .exe File:
   Download the provided .exe file (e.g., expense_tracker.exe).

2. Run the Program:
   - On a Windows machine, double-click the .exe file to run the application.
   - If you prefer, you can open a command prompt and run the executable by navigating to the folder containing the .exe file and typing:
     expense_tracker.exe

Usage
Once the program starts, you will be presented with a simple menu:

--- Personal Expense Tracker By Dabbiru Sreeraj ---
1. Add Expense
2. View All Expenses
3. View Summary by Category
4. Exit
Enter your choice: 

1. Add Expense:
- Enter the date in the format DD-MM-YYYY.
- Choose a category from the following list:  
  - Food
  - Travel
  - Entertainment
  - Healthcare
  - Utilities
  - Shopping
  - Miscellaneous
- Enter the amount spent.

2. View All Expenses:
This will display all expenses recorded in the application, showing the date, category, and amount.

3. View Summary by Category:
This feature provides a summary of expenses categorized by Food, Travel, Entertainment, Healthcare, Utilities, Shopping, and Miscellaneous.

4. Exit:
Exit the application.

File Format
The application saves expenses in a simple text file named expenses.txt. This file will be created in the same directory as the executable if it does not already exist. The file stores each expense in the following format:
DD-MM-YYYY Category Amount

For example:
01-01-2025 Food 25.50

Please ensure that this expenses.txt file remains intact, as it stores all the expense records. Deleting or modifying this file may cause the program to lose data.

Structure and Code Details
- Expense Structure: A structure that stores each expense’s date, category, and amount.
- Menu: The program displays a menu and processes user input to add/view expenses.
- File Handling: The program uses file I/O to store and retrieve expenses in a file (expenses.txt).

Limitations
- The application does not handle invalid inputs gracefully. Invalid entries may cause the program to crash or behave unexpectedly.
- No graphical user interface (GUI) is implemented, making the application command-line-based only.

Future Improvements
- Add input validation to handle incorrect user entries.
- Implement a GUI for easier interaction.
- Add the ability to edit or delete expenses.
- Implement data storage in a database for better management.

Contact
For any queries or support, feel free to reach out to me at:  
Email: dabbirusreeraj@gmail.com
