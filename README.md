# 📈 CodeAlpha Stock Trading Platform

A Java-based console application developed as part of the **CodeAlpha Java Programming Internship – Task 2**.

The Stock Trading Platform simulates a basic stock market environment where users can view market data, buy and sell stocks, manage their portfolio, track transactions, and monitor portfolio performance.

## 🚀 Features

* 📊 View available stock market data
* 💰 Buy stocks
* 💸 Sell stocks
* 📁 Manage stock portfolio
* 💳 Track account balance
* 📜 View transaction history
* 📈 Update simulated market prices
* 📊 Analyze portfolio performance
* 💵 Calculate profit and loss
* ⚠️ Validate user inputs
* 💾 Save and load application data using File I/O
* 🖥️ Interactive console-based menu

## 🛠️ Technologies Used

* **Java**
* **Object-Oriented Programming (OOP)**
* **ArrayList**
* **Java Collections**
* **File I/O**
* **Console-based Interface**

## 🧠 OOP Concepts Used

This project demonstrates several core Object-Oriented Programming concepts:

* Classes and Objects
* Encapsulation
* Constructors
* Methods
* Object interaction
* ArrayList and Collections
* Separation of responsibilities between classes

## 📂 Project Structure

```text
CodeAlpha_StockTradingPlatform/
│
├── Main.java
├── Stock.java
├── Portfolio.java
├── Transaction.java
├── User.java
├── StockMarket.java
├── DataManager.java
├── README.md
└── .gitignore
```

## 📌 Project Components

### `Main.java`

Contains the main application, user interface, and menu-driven program flow.

### `Stock.java`

Represents individual stocks and stores their market information.

### `Portfolio.java`

Manages the user's stock holdings and portfolio calculations.

### `Transaction.java`

Stores information about buying and selling transactions.

### `User.java`

Manages user-related information and account details.

### `StockMarket.java`

Manages available stocks and simulated market prices.

### `DataManager.java`

Handles saving and loading application data using File I/O.

## 🎮 Main Menu

The application provides the following options:

```text
==========================================
              MAIN MENU
==========================================

1. View Market Data
2. Buy Stock
3. Sell Stock
4. View Portfolio
5. View Transactions
6. View Account Balance
7. Update Market Prices
8. View Portfolio Performance
9. Save & Exit

==========================================
```

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/ywxarchit/CodeAlpha_StockTradingPlatform.git
```

### 2. Open the Project Folder

```bash
cd CodeAlpha_StockTradingPlatform
```

### 3. Compile the Java Files

```bash
javac *.java
```

### 4. Run the Application

```bash
java Main
```

## 💡 How the Application Works

The application starts with an initial account balance and provides a menu-driven interface.

Users can:

1. View available stocks and their current prices.
2. Buy stocks by entering the stock symbol and quantity.
3. Sell stocks from their existing portfolio.
4. View their current portfolio holdings.
5. Check previous transactions.
6. Check their available account balance.
7. Update simulated market prices.
8. Analyze portfolio performance and profit/loss.
9. Save application data and exit.

## 🧪 Input Validation

The application handles invalid user inputs such as:

* Invalid stock symbols
* Zero or negative quantities
* Insufficient account balance
* Selling more shares than currently owned

## 💾 Data Persistence

The project uses **File I/O** to save and retrieve application data, allowing important information such as portfolio and transaction data to be maintained between program executions.

## 🎓 Internship Information

**Organization:** CodeAlpha
**Program:** Java Programming Internship
**Task:** Task 2 – Stock Trading Platform

## 👨‍💻 Author

**Archit Singh**

**B.Tech – Computer Science & Engineering**

## 📌 Purpose

This project was developed for educational and internship purposes to strengthen practical knowledge of:

* Java Programming
* Object-Oriented Programming
* Collections
* File Handling
* Input Validation
* Console Application Development
