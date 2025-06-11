# Bank Management System


### Project Description
As a part of learning the concept of classes and objects in python a project was carried out to learn and explore more about the language. More than those learnt from the courses, I could learn more about the concepts of objects and classes by researching on my own and clearing my doubts.
    You can simulate Withdrawal, Deposition, Money sending, etc... in the demonstrated project


### The Problem
To study the Concepts of Objects and Classes in Python

### The Solution
The concept of Objects and classes have been familiarized

## Technical Details
### Technologies/Components Used
For Software:
- Python
- MySQL

### Implementation
For Software: Python3, MySQL 8.0
# Installation
For Linux: Run the following commands in the terminal one by one
- sudo apt install python3.13
- sudo apt install python3-pip
- sudo apt install mysql-server -y
- sudo mysql_secure_installation
-   Follow the prompts to:
1.       Set a root password ✅
2.       Remove anonymous users ✅
3.       Disallow root login ✅
4.       Remove test databases ✅
5.       Reload privilege tables ✅
- sudo systemctl start mysql
- sudo systemctl enable mysql
- Login to MySQL and Create the database "bank_accounts"
-       sudo mysql -u root -p
-       CREATE DATABASE bank_accounts;
- pip install mysql.connector

For Windows Download python installer from python.org and MySQL local server and install and run the following command.
- pip install mysql.connector
- login to mysql and create the database "bank_account"

## Run
python3 main.py



# Project Demo
## Screenshots
### Creating Account and Loggin in
<img width="277" height="400" alt="screenshot1" src="Bank/Screenshots/accnt-creat.png">

### Getting Account Details
<img width="277" height="395" alt="screenshot2" src="Bank/Screenshots/accnt-details.png">

### Depositing Money
<img width="277" height="231" alt="screenshot3" src="Bank/Screenshots/deposit.png">

### Sending Money
<img width="306" height="279" alt="screenshot4" src="Bank/Screenshots/send.png">

### Withdrawing Money
<img width="277" height="231" alt="screenshot4" src="Bank/Screenshots/withdrawal.png">

### Account Statement
<img width="306" height="285" alt="screenshot4" src="Bank/Screenshots/statement.png">
