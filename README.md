# ATM-Management-system

🏦 ATM Banking System – Python OOP Project

# Project Description

This project is a Python-based ATM Banking System developed using Object-Oriented Programming (OOP) concepts.
It simulates basic ATM operations such as checking balance, depositing money, withdrawing money, and viewing account details.

The project demonstrates the practical use of:

Abstract Classes

Encapsulation

Inheritance

Method Overriding

Class Methods & Static Methods

# Features

Secure account balance handling using encapsulation

Menu-driven ATM interface

Deposit and withdrawal validation

Displays bank name using a class method

Implements real-world banking logic

# OOP Concepts Used

1️⃣ Abstract Class

BankAccount is an abstract base class that defines the transaction() method.


2️⃣ Encapsulation

Private variable __balance to protect account balance

Public getter and setter methods to access and update balance safely


3️⃣ Inheritance

ATM class inherits from the Account class

Reuses account properties and methods


4️⃣ Method Overriding

transaction() method is overridden in the ATM class to provide ATM menu functionality


5️⃣ Class & Static Methods

display_bank_name() → Displays bank name

validate_amount() → Validates deposit/withdrawal amount



📋 ATM Menu Options

1. Check Balance


2. Deposit Money


3. Withdraw Money


4. View Account Details


5. Exit

▶️ How to Run the Project

1. Make sure Python is installed on your system


2. Clone the repository:

git clone <your-repository-link>


3. Run the Python file:

python atm.py

🧑‍💻 Sample Account Used

user = ATM("Rahul", 12345, 1000)

 # Learning Outcome

This project helps beginners understand:

How OOP concepts work together in a real application

How to design modular and secure Python programs

How ATM systems function at a basic level
