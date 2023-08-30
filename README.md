# Bank Account Management System

This repository contains a Python script for a simple bank account management system. The script defines classes for managing bank accounts, specifically `BankAccount`, `SavingsAccount`, and `CurrentAccount`.

## BankAccount Class

### Description
The `BankAccount` class represents a basic bank account with methods for depositing, withdrawing, and checking the balance.

### Methods
- `__init__(self, account_number, account_holder)`: Constructor to initialize a `BankAccount` instance.
- `deposit(self, amount)`: Method to deposit funds into the account.
- `withdraw(self, amount)`: Method to withdraw funds from the account.
- `get_balance(self)`: Method to retrieve the current balance.

## SavingsAccount Class

### Description
The `SavingsAccount` class inherits from `BankAccount` and adds functionality for applying interest to the account balance.

### Methods
- `__init__(self, account_number, account_holder)`: Constructor to initialize a `SavingsAccount` instance.
- `apply_interest(self)`: Method to apply interest to the account balance.

## CurrentAccount Class

### Description
The `CurrentAccount` class inherits from `BankAccount` and represents a current account.

### Methods
- `__init__(self, account_number, account_holder)`: Constructor to initialize a `CurrentAccount` instance.

## Main Function

The `main` function allows users to interact with the bank account system through a simple command-line interface. The available options include creating accounts, depositing funds, withdrawing funds, checking balances, transferring funds, and exiting the program.

### Usage
Run the script and follow the on-screen prompts to perform banking operations.

## How to Run
1. Make sure you have Python installed on your system.
2. Save this script to a file, e.g., `bank_account_system.py`.
3. Open a terminal or command prompt.
4. Navigate to the directory containing the script.
5. Run the script using the command: `python bank_account_system.py`
