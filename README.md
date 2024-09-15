# Bank_Management_System
Bank_Management_System by Suchit Navghare in c++

Author
This project was developed and written by Suchit Navghare.
    • Email: suchitatwork@gmail.com
    • GitHub: suchitnavghare13
    • LinkedIn: Suchit Navghare
Feel free to reach out if you have any questions or suggestions regarding this project!

# Overview

The Bank Management System is a simple C++ program that simulates basic banking functionalities such as creating accounts, depositing and withdrawing money, checking balances, and transferring funds between accounts. It is designed for educational purposes, demonstrating object-oriented programming concepts, file handling, and basic banking operations.

# Features

- Create New Accounts: Users can create a new account with a minimum balance of ₹3000.
- Deposit Money: Users can deposit money into their existing account.
- Withdraw Money: Money can be withdrawn from an account if the remaining balance does not go below ₹3000.
- Check Balance: Users can check their current balance and account details.
- Transfer Money: Funds can be transferred between accounts, provided the sender maintains a minimum balance of ₹3000.

# Code Structure

- Class: `Account`: Manages individual account details (name, account number, balance) and provides functions for deposit, withdrawal, balance checking, and money transfers.
  - Data Members:
    - `name`: Name of the account holder.
    - `acc_no`: Unique account number for each account.
    - `balance`: The account balance.
    - `ACC_generator`: A static integer used to generate unique account numbers.
  - Member Functions:
    - `create_account(name, amount)`: Creates a new account.
    - `deposit(amount)`: Adds money to the account.
    - `withdraw(amount)`: Withdraws money from the account if balance remains above ₹3000.
    - `balance_check()`: Displays the account balance.
    - `transfer(receiver, amount)`: Transfers money to another account if minimum balance criteria is met.

# How to Run the Program

1. Clone the Repository:
   Clone this repository using Git:

   ```bash
   git clone git@github.com:suchitnavghare13/Bank_Management_System.git
   ```

2. Compile the Program:
   Navigate to the project directory and compile the C++ program:

   ```bash
   g++ BankManagementSystem.cpp -o BankManagementSystem
   ```

3. Run the Program:
   Execute the compiled file:

   ```bash
   ./BankManagementSystem
   ```

4. Use the Application:
   The application will display a menu where you can:
   - Create a new account.
   - Deposit or withdraw money.
   - Check your account balance.
   - Transfer money between accounts.

# Example Menu

```plaintext
-----------------------
----- Suchit Bank -----
-----------------------
1. Open New Account
2. Deposit To Account
3. Withdraw From Account
4. Check Account Balance
5. Transfer amount
0. Exit
```

# Sample Output

```plaintext
Enter name: John
Enter Amount >=3000 to open account: 5000

Hi John, Your Account number is: 202401
Your account 202401 on the name of John current balance is 5000.

Enter amount to deposit: 1500
Your account 202401 on the name of John current balance is 6500.
```

# Prerequisites

- A C++ compiler like `g++` (part of the GNU Compiler Collection).
- Basic understanding of terminal commands for compilation and execution.

# Future Enhancements

- Add file handling to store account details persistently.
- Implement user authentication for enhanced security.
- Introduce more advanced banking features such as loan management and transaction history tracking.

# Contributing

Feel free to fork this project and submit pull requests if you want to contribute or improve the code. Any form of contribution is welcome!
