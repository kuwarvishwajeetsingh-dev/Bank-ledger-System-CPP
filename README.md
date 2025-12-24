# Bank-ledger-System-CPP
A console-based Bank Ledger System implemented in C++ using OOP concept
---

🏦 Secure Banking Management System (C++)

A robust, menu-driven Banking Management System** developed in **C++** that simulates real-world banking operations with **persistent storage, authentication, and admin controls**.
Designed with **Object-Oriented Programming (OOP)** principles and **file handling**, this project demonstrates production-grade console application design

*Object-Oriented Design** using `Account`, `Transaction`, and `Ledger` classes
  *Persistent Data Storage** using file handling (`fstream`)
  *Secure Authentication**

  * User PIN-based access
  * Admin-only privileged view
  *Robust Input Validation**

  * Prevents crashes and invalid data
  *Real Banking Rules**

  * Minimum balance enforcement
  *Cross-Platform Compatibility**

  * Works on Windows & Linux
  *Clean, Modular, and Scalable Code**

 🧠 Core Features

 👤 Account Management

* Create new bank accounts
* Secure 4-digit PIN authentication
* Permanent data storage in `.txt` file

 💰 Transactions

* Deposit money
* Withdraw money (with minimum balance check)
* Automatic balance updates

 🔍 Search & Display

* View account details by ID
* Search accounts by name (partial match supported)

🗑️ Account Deletion

* PIN-protected account removal

🛠️ Admin Panel

* Password-protected admin access
* View all accounts in tabular format

🔐 Security Design

| Level          | Protection                   |
| -------------- | ---------------------------- |
| Program Access | Admin password required      |
| Account Access | PIN-based authentication     |
| Admin View     | Separate admin password      |
| Input Handling | Fail-safe numeric validation |

 📂 Data Persistence

* All account data is **stored permanently** in:

BankData/accounts.txt

* Data is **automatically loaded** when the program restarts
* Account IDs **never reset**, ensuring consistency


 🧪 Sample Demonstration (5 Account Holders)

 ✅ Created Accounts

| Account ID | Name         | PIN  | Balance (₹) |
| ---------- | ------------ | ---- | ----------- |
| 00001      | Rahul Sharma | 1234 | 12500.00    |
| 00002      | Priya Verma  | 4321 | 9800.00     |
| 00003      | Aman Singh   | 5678 | 15000.00    |
| 00004      | Neha Gupta   | 2468 | 7200.00     |
| 00005      | Arjun Mehta  | 1357 | 20000.00    |

 📌 Sample Console Output

 🔹 Admin View

--- All Accounts ---
ID        Name                 PIN        Balance
-------------------------------------------------------
1         Rahul Sharma         1234       12500.00
2         Priya Verma          4321       9800.00
3         Aman Singh           5678       15000.00
4         Neha Gupta           2468       7200.00
5         Arjun Mehta          1357       20000.00


 🔹 Account Display

Account ID : 00003
Name       : Aman Singh
Balance    : Rs 15000


 🔹 Withdrawal Rule Enforcement

Maintain Rs 500 minimum

🛠️ Technologies Used

Language:C++
Concepts:

  * OOP (Encapsulation, Abstraction)
  * File Handling
  * Input Validation
  * STL (`vector`, `algorithm`)
  Compiler:** GCC / MinGW



Admin Credentials**

```
Password: admin123

 📈 Learning Outcomes

This project strengthened my understanding of:

* Real-world **system design**
* **Secure authentication** workflows
* **Persistent storage** mechanisms
* Clean, readable, and scalable C++ code
* Defensive programming techniques

 🌟 Future Enhancements

* Transaction history persistence
* Encrypted PIN storage
* Interest calculation
* GUI version (Qt / Web frontend)
* Database integration (SQLite)

 👨‍💻 Author

Kuwar Vishwajeet Singh
B.Tech (CSE) GCET | BS Data Science – IIT Madras


⭐ If you find this project valuable, consider starring the repository!
