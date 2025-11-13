# Bankmanagement-java
Bank Management System (Java Console Application)
📘 Overview

The Bank Management System is a simple Java console-based project that allows users to create and manage bank accounts.
It provides essential banking features such as account creation, deposit, withdrawal, fund transfer, mini statement, and balance inquiry — all handled through a menu-driven interface.

⚙️ Features

🧾 Create New Account – Register a new customer with account number, type, name, and initial deposit.

💰 Deposit Money – Add funds to an existing account.

💸 Withdraw Money – Withdraw amount if sufficient balance is available.

🔁 Transfer Funds – Transfer money from one account to another.

👤 View Account Information – Display details like account number, type, name, and balance.

📄 Mini Statement – View recent transactions for a given account.

💵 Check Balance – Instantly view current account balance.

🚪 Exit – Quit the application safely.

🧩 Technologies Used

Language: Java

Concepts: Object-Oriented Programming (OOP)

Collections Used: HashMap, ArrayList

Classes Used:

BankAccount – Handles individual account details and transactions

BankManagementSystem – Manages all accounts and banking operations

Project – Contains the main() method and user interaction logic

🏗️ Class Structure
🔹 BankAccount

Fields:
accountNumber, accountType, customerName, balance, transactionHistory

Methods:
deposit(), withdraw(), transfer(), displayInfo(), displayMiniStatement()

🔹 BankManagementSystem

Manages multiple bank accounts using a HashMap<String, BankAccount>

Methods:
createAccount(), deposit(), withdraw(), transfer(), getAccountInfo(), getMiniStatement(), checkBalance()

🔹 Project (main class)

Displays menu options to perform different operations.

Uses a Scanner to take user input.

🚀 How to Run the Program

Save the file as Project.java

Open a terminal or command prompt, then compile and run:

javac Project.java
java Project


The console will display a menu with available operations.
Example:

1. Create Account
2. Deposit
3. Withdraw
4. Transfer
5. Account Info
6. Mini Statement
7. Check Balance
8. Exit


Enter the option number to perform a specific operation
OUTPUT:

1. Create Account
2. Deposit
3. Withdraw
4. Transfer
5. Account Info
6. Mini Statement
7. Check Balance
8. Exit
Choose an option: 1
Enter account number: 123456
Enter account type: Savings
Enter customer name: John Doe
Enter initial deposit amount: 1000
Account created successfully!
1. Create Account
2. Deposit
3. Withdraw
4. Transfer
5. Account Info
6. Mini Statement
7. Check Balance
8. Exit
Choose an option: 2
Enter account number: 123456
Enter deposit amount: 500
Deposit successful! Current balance: 1500
1. Create Account
2. Deposit
3. Withdraw
4. Transfer
5. Account Info
6. Mini Statement
7. Check Balance
8. Exit
Choose an option: 3
Enter account number: 123456
Enter withdrawal amount: 200
Withdrawal successful! Current balance: 1300
1. Create Account
2. Deposit
3. Withdraw
4. Transfer
5. Account Info
6. Mini Statement
7. Check Balance
8. Exit
Choose an option: 5
Enter account number: 123456
Account Number: 123456
Account Type: Savings
Customer Name: John Doe
Balance: 1300
1. Create Account
2. Deposit
3. Withdraw
4. Transfer
5. Account Info
6. Mini Statement
7. Check Balance
8. Exit
Choose an option: 8
Exiting...
