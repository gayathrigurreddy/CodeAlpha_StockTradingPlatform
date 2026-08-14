# Stock Trading Platform

A Java console-based stock trading simulation developed as part of my CodeAlpha Java internship projects.

## 📌 Project Overview

The Stock Trading Platform is a console-based application that simulates basic stock market activities. Users can view market data, buy and sell stocks, manage their portfolio, track cash balance, calculate profit and loss, and simulate changes in stock prices.

## ✨ Features

- Display available stocks and current market prices
- Buy stocks using available cash
- Sell stocks from the user's portfolio
- Track cash balance
- Maintain stock holdings and quantities
- Calculate average buy price
- Calculate current market value of holdings
- Calculate unrealized profit or loss
- Display total account value
- Simulate random market price changes
- Validate stock symbols and quantities
- Prevent purchases when there is insufficient cash
- Prevent selling stocks that are not owned
- Save buy and sell transactions to a file
- Display transaction date and time

## 🛠️ Technologies Used

- Java
- Object-Oriented Programming (OOP)
- Java Collections (`HashMap`, `LinkedHashMap`, `Map`)
- File Handling (`FileWriter`)
- Date and Time API (`LocalDateTime`, `DateTimeFormatter`)
- Exception Handling
- Random Number Generation
- Console-based User Input using `Scanner`

## 📂 Project Structure

CodeAlpha_StockTradingPlatform/
└── src/
    └── StockTradingPlatform.java
    
## ▶️ How to Run

Make sure Java 17 or later is installed.

### Compile

javac src/StockTradingPlatform.java

### Run

java -cp src StockTradingPlatform

## 💰 Starting Balance

The application starts with a simulated cash balance of:

$100,000.00

## 📈 Available Stocks

The simulation includes:

- AAPL - Apple
- MSFT - Microsoft
- GOOG - Alphabet
- AMZN - Amazon
- TSLA - Tesla

## 📝 Transaction Logging

Buy and sell transactions are saved in `transactions.txt`.

Each transaction records:

- Date and time
- Transaction type
- Stock symbol
- Quantity
- Price

## ⚠️ Important

This project is an educational stock trading simulation.

It does not connect to a real stock exchange, use real-time market data, or execute real financial transactions.

## 🎯 Learning Outcomes

Through this project, I practiced:

- Java programming fundamentals
- Object-Oriented Programming
- Classes and objects
- Collections and Maps
- File handling
- Exception handling
- Date and time handling
- User input validation
- Data processing and calculations
- Console-based application development

## 👩‍💻 Author

Gurreddy Gayathri

GitHub: @gayathrigurreddy

## 📚 Internship

Developed as part of my Java internship projects with CodeAlpha.
