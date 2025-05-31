🏦 Bank Application with Python OOP
Welcome to the Bank Application project built using Python's Object-Oriented Programming (OOP) principles. This project models a simplified banking system that helps you understand and apply core OOP concepts like inheritance, encapsulation, and method overriding in a real-world scenario.

📌 Project Description
This is a console-based application that allows the user to:

Manage customers and employees

Create and operate different bank accounts (Savings and Current)

Deposit and withdraw money

Save and load the application's state using the pickle module

🧠 Key Concepts Used
Encapsulation: Secure handling of account balance and customer details

Inheritance: Customer and Employee classes inherit from Person; SavingsAccount and CurrentAccount inherit from Account

Method Overriding: Custom withdraw() and display_details() methods for account types

Data Persistence: Saving and loading data with Python’s pickle module

🏗️ Project Structure
🔹 Classes Overview
Class	Description
Person	Base class for Customer and Employee
Customer	Inherits from Person; represents a bank customer
Employee	Inherits from Person; represents a bank employee
Account	Abstract base class for bank accounts
SavingsAccount	Inherits from Account; includes interest calculation
CurrentAccount	Inherits from Account; allows overdrafts
Bank	Manages all accounts, customers, employees, and data operations

🔹 Bank Class Responsibilities
Add/get accounts, customers, and employees

Save/load data using pickle

Optional methods: list all accounts, customers, employees

🧪 Features
✅ Add customers and employees

✅ Open savings and current accounts

✅ Deposit and withdraw funds

✅ View detailed account/customer/employee info

✅ Save data to a file

✅ Load data from a file

⚙️ (Optional): Transfer funds, view transaction history

💾 How to Use
Clone or download this repository.

Run the main.py file.

Use the command-line menu to perform banking operations.

bash
Copy
Edit
python main.py
🛠️ Technologies Used
Python 3.x

Object-Oriented Programming

Pickle (for data serialization)

🚀 Future Improvements (Optional)
Add GUI using Tkinter or PyQt

Implement role-based access for employees

Add transaction logs

Improve error handling and user input validation

📁 Resources
📄 Project Documentation

Google Doc (Full Guide)

🙌 Acknowledgments
Thanks to all contributors and resources that inspired this project. This project was completed as part of a Python learning journey focusing on practical implementation of OOP.
