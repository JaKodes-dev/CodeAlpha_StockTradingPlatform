# Stock Trading Platform

A Java simulation for stock market trading. It simulates price fluctuations, lets users buy and sell shares, and tracks portfolio value and profit/loss in real time.

## Features
- Market price simulation with live updates
- Buy and sell order execution with balance and share validation
- Portfolio tracking (cash balance, current holdings, unrealized and realized P&L)
- Transaction history log
- CSV export for portfolio data
- Available in both Swing Desktop GUI and Console CLI modes

## How to Run

### Compile
```bash
javac -d bin -sourcepath src src/com/codealpha/stocktrading/Main.java
```

### Run GUI
```bash
java -cp bin com.codealpha.stocktrading.Main --gui
```
Or run `run_gui.bat` on Windows.

### Run CLI
```bash
java -cp bin com.codealpha.stocktrading.Main --cli
```
Or run `run_cli.bat` on Windows.

## Author
Joseph Appiah Karikari
