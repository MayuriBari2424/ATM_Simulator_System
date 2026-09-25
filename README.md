# 🏧 ATM Simulator System

## 📌 Project Overview

The **ATM Simulator System** is a Java-based application that simulates the basic operations of an Automated Teller Machine (ATM).

The system allows users to securely log in using a **PIN** and perform common banking operations such as checking account balance, withdrawing money, depositing money, and changing the PIN.

This project demonstrates the use of **Core Java concepts** to develop a simple, interactive, menu-driven banking application.

---

## 🎯 Objectives

* To simulate the basic functionality of an ATM.
* To provide secure PIN-based authentication.
* To perform basic banking transactions.
* To provide a simple and user-friendly interface.
* To demonstrate practical implementation of Java programming concepts.

---

## ✨ Features

* 🔐 PIN-based Authentication
* 💰 Check Account Balance
* 💵 Withdraw Money
* 💳 Deposit Money
* 🔑 Change PIN
* 📋 Menu-driven Interface
* ⚠️ Insufficient Balance Validation
* ❌ Invalid Input Handling
* 🚪 Exit Option

---

## 🛠️ Technologies Used

| Technology       | Description                                  |
| ---------------- | -------------------------------------------- |
| **Java**         | Main programming language                    |
| **JDK**          | Java Development Kit                         |
| **IDE**          | VS Code / IntelliJ IDEA / Eclipse / NetBeans |
| **OOP Concepts** | Classes, Objects, Methods, Encapsulation     |

---

## 📚 Java Concepts Used

The project demonstrates several Core Java concepts:

* Classes and Objects
* Methods
* Variables and Data Types
* Conditional Statements
* Loops
* Switch Case
* Encapsulation
* Exception Handling
* User Input using `Scanner`
* Object-Oriented Programming

---


> **Note:** Modify the file names above according to the actual Java files in your project.

---

## ⚙️ Requirements

Before running the project, make sure you have:

* Java JDK installed
* Java-supported IDE or Command Prompt
* Basic Java environment configured

Check Java installation using:

```bash
java --version
```

Check Java compiler using:

```bash
javac --version
```

---

## ▶️ How to Run the Project

### Using an IDE

1. Open the project in **VS Code, Eclipse, IntelliJ IDEA, or NetBeans**.
2. Open the Java source files.
3. Locate the `main()` method.
4. Run the main Java class.
5. Enter the PIN when prompted.
6. Select the required ATM operation from the menu.

### Using Command Prompt

Navigate to the source folder:

```bash
cd src
```

Compile the Java file:

```bash
javac Main.java
```

Run the program:

```bash
java Main
```

---

## 🖥️ Sample Output

```text
=================================
       ATM SIMULATOR SYSTEM
=================================

Enter your PIN: ****

Login Successful!

-------- ATM MENU --------
1. Check Balance
2. Withdraw Money
3. Deposit Money
4. Change PIN
5. Exit

Enter your choice: 1

Current Balance: ₹10,000
```

### 💵 Withdrawal

```text
Enter your choice: 2

Enter amount to withdraw: ₹2000

Please collect your cash.

Remaining Balance: ₹8000
```

### 💳 Deposit

```text
Enter your choice: 3

Enter amount to deposit: ₹3000

Amount deposited successfully!

Updated Balance: ₹11000
```

### 🔑 Change PIN

```text
Enter your choice: 4

Enter current PIN: ****
Enter new PIN: ****

PIN changed successfully!
```

---

## 🔄 System Workflow

```text
        ┌───────────────┐
        │     Start     │
        └───────┬───────┘
                ↓
        ┌───────────────┐
        │  Enter PIN    │
        └───────┬───────┘
                ↓
        ┌───────────────┐
        │ Authenticate  │
        └───────┬───────┘
                ↓
        ┌───────────────┐
        │   ATM Menu    │
        └───────┬───────┘
                ↓
     ┌──────────┼──────────┐
     ↓          ↓          ↓
  Balance    Withdraw    Deposit
     │          │          │
     └──────────┼──────────┘
                ↓
          Change PIN
                ↓
        ┌───────────────┐
        │      Exit     │
        └───────────────┘
```

---

## 🔒 Security

The system uses PIN-based authentication to provide basic account security.

This project is intended for **educational purposes**. A real ATM system would require advanced security mechanisms such as encryption, multi-factor authentication, secure databases, transaction monitoring, and network security.

---

## 🚀 Future Enhancements

The project can be enhanced by adding:

* 🗄️ MySQL/Oracle database integration
* 👥 Multiple user accounts
* 📜 Transaction history
* 🧾 Transaction receipt generation
* 🔐 Account lock after multiple incorrect PIN attempts
* 💬 SMS/Email transaction notifications
* 🖥️ GUI using Java Swing or JavaFX
* 🏦 Multiple bank support
* 📊 Admin panel
* 🔒 Enhanced security and encryption

---

## 📖 Learning Outcomes

By developing this project, we learn:

* How to develop a menu-driven Java application.
* How to use Object-Oriented Programming concepts.
* How to handle user input using `Scanner`.
* How to implement authentication.
* How to perform banking transactions.
* How to validate user input.
* How to structure a Java project.

---

## 👩‍💻 Author

**Mayuri Bari**

MCA Student | Java Developer

---

## ⭐ Conclusion

The **ATM Simulator System** is a Java-based project developed to simulate the basic operations of an ATM. It provides users with essential banking functionalities such as balance inquiry, cash withdrawal, cash deposit, and PIN management.

The project provides practical experience in **Core Java and Object-Oriented Programming** and can be further enhanced by integrating a database and graphical user interface.

---

## 📜 License

This project is created for **educational and academic purposes**.
