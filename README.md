# CPI Spot Trading CLI App

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/status-in%20development-yellow)
![Last Commit](https://img.shields.io/github/last-commit/M4l3k-16/CPI)
![GitHub Repo Size](https://img.shields.io/github/repo-size/M4l3k-16/CPI)
A command-line Python application for **spot trading simulation** and **live analysis**, designed to help traders test, monitor, and evaluate setups using custom triggers, real-time alerts, and performance metrics. Built with a focus on trading discipline, signal quality, and risk management.

---

## 🚀 Project Overview

The CPI (Custom Price Intelligence) app is a **Python CLI tool** that helps you:

- Simulate spot trades based on price triggers.
- Notify via Telegram when price levels are reached or trades are executed.
- Block trades during high-impact news.
- Track your trading performance with detailed metrics.
- Maintain discipline with built-in risk controls.

---

## 🔧 Features (Planned)

### ✅ Core Trading Logic

- [ ] Create simulated **limit-like triggers** using market orders.
- [ ] Support **multiple triggers** with FIFO or price proximity priority.
- [ ] Set **TP / SL** for each trigger.
- [ ] Confirm trades with full details before execution.
- [ ] Tag each trade by **strategy** (e.g., OB, FVG, breakout).

### 🔔 Alerts & News

- [ ] **Telegram bot integration** to notify:
  - Triggered price levels
  - Executed trades
  - Daily news summary (economic + crypto)
- [ ] Display all **high-impact news** for the day (in Algeria time, UTC+1).
- [ ] Block or warn before placing trades during sensitive news periods.

### 📊 Performance Tracking

- [ ] Track trade outcomes (Win/Loss)
- [ ] Calculate:
  - Win rate
  - Profit %
  - Risk-to-Reward (RR)
  - Drawdown
- [ ] Filter by date, tag, or strategy.

### 🛡️ Risk & Behavior Management

- [ ] **Daily and Weekly Loss Lock**: Automatically pause trading after hitting loss thresholds.
- [ ] **Daily Trade Limit**: Limit number of trades per day.
- [ ] **Cooldown Timer** after a loss (e.g., 15–30 minutes pause).
- [ ] Add **trade notes or reasons** for review and journaling.

### 📈 Market Tools (Optional Add-ons)

- [ ] Load **historical data** for backtesting.
- [ ] Basic charts in terminal (ASCII or external link).
- [ ] Level scoring based on:
  - Order blocks
  - FVGs
  - Liquidity pools
  - MA, Fib levels, etc.

---

## ⚙️ Tech Stack

- Python 3.x
- Telegram Bot API
- Binance API (for real-time price data)
- Rich (for CLI UI)
- SQLite or JSON for local data storage
- Optional: Pandas, TA-Lib, or custom indicator code

---

## ✅ Setup & Installation (Coming Soon)

---

## 💡 Notes

This tool is designed for **education, journaling, and simulation only**. No real trades will be executed unless explicitly implemented.

---

## 📌 Roadmap

- [ ] Build trigger system
- [ ] Add Telegram integration
- [ ] Build performance tracking module
- [ ] Integrate news filters and blocking
- [ ] Release v1.0 simulation-only version

---

## 📬 Contact

Created by [@m4l3k-16] – for suggestions or contributions, feel free to open an issue or PR!
