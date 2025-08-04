# 🚀 Telegram to MT5 Auto Trading Bot - Revolutionize Your Trading! 🚀

Welcome to the ultimate trading automation solution! This **Telegram to MT5 Auto Trading Bot** is a cutting-edge, Python-based tool designed to transform your trading experience. Built with precision and tailored for success, it connects your Telegram account to MetaTrader 5 (MT5) to execute trades automatically based on real-time signals. Whether you're a forex enthusiast, gold trader, or crypto investor, this bot is your key to efficiency and profitability!

---

## 🌟 Why Choose My Trading Bot?

I'm a passionate developer with expertise in creating custom trading solutions. This bot is crafted to meet the demands of modern traders like you. Here’s what sets it apart:

- **🔒 Userbot Technology**: Operates as a real Telegram user (no bot token needed), ensuring secure and direct access.
- **📡 Private Channel Monitoring**: Tracks a single private Telegram channel for instant signal detection.
- **⚡ Real-Time Signal Parsing**: Handles complex, multi-line, and multi-message signals with ease.
- **🤖 Automated Order Execution**: Places market and limit orders in MT5 with lightning-fast precision.
- **🛡️ Smart Risk Management**: Dynamically calculates lot sizes, capping losses at your chosen percentage (e.g., 3% of account balance).
- **📊 Intelligent Trade Management**: Moves Stop Loss (SL) to breakeven on TP1 hit and cancels pending orders for profit optimization.
- **🎛️ Customizable Telegram Controls**: Start/stop the bot, adjust risk, order counts, and split ratios via an intuitive inline menu or commands.
- **🔄 Reset to Default**: Instantly revert settings to default with a single click or command.
- **📝 Comprehensive Logging**: Sends detailed notifications (trades, TP/SL hits, errors) to a dedicated Telegram logging bot.
- **💻 EA-Free Design**: Pure Python solution—no need for MT5 Expert Advisors, keeping it lightweight and versatile.

---

## Watch Demo

[![Watch Demo](https://raw.githubusercontent.com/kaleemullahkhan786/MT5-Signal-Sync-Bot/main/Trading%20Bot.mp4)

---

## 🚀 How It Works – Simple & Powerful

1. **Signal Detection**: The bot listens to your private Telegram channel (e.g., "Gold buy now 2350.0 - 2345.0", "SL: 2340", "TP: 2355").
2. **Instant Execution**: Parses signals and executes market/limit orders in MT5 based on your settings.
3. **Risk Control**: Adjusts lot sizes dynamically to match your risk tolerance.
4. **Trade Optimization**: Manages trades by setting SL to breakeven on TP1 and canceling unexecuted orders.
5. **Real-Time Updates**: Keeps you informed via a logging bot with every move and potential issue.

---

## 🛠️ Getting Started – Easy Setup for Everyone

No coding skills? No problem! I’ll guide you every step of the way.

### 1. Set Up Your Environment

- Install Python 3.8+ from python.org.

- Clone this repo or download the files.

- Run in your terminal:

  ```bash
  pip install -r requirements.txt
  ```

- I provide full support to ensure a smooth setup!

### 2. Configure Your Bot

- Edit `config.json` with:

  - **Telegram Credentials**: API ID/Hash (from my.telegram.org) and your phone number.
  - **Channel Info**: Your private channel ID or @username.
  - **Logging Bot**: Token and chat ID from a bot created via @BotFather.
  - **MT5 Details**: Login, password, and server from your broker.
  - **Preferences**: Set risk (e.g., 3%), market orders (e.g., 3), limit orders (e.g., 30), and split ratio (e.g., 70/30).

- Sample `config.json`:

  ```json
  {
    "telegram_api_id": "YOUR_API_ID",
    "telegram_api_hash": "YOUR_API_HASH",
    "telegram_phone": "your_account_number",
    "telegram_channel_id": "@YourSignalChannel",
    "logging_bot_token": "YOUR_BOT_TOKEN",
    "logging_chat_id": "YOUR_CHAT_ID",
    "mt5_login": "123456",
    "mt5_password": "YOUR_PASSWORD",
    "mt5_server": "BrokerName-Demo",
    "risk_per_signal_percent": 3,
    "num_market_orders": 3,
    "num_limit_orders": 30,
    "limit_order_split_ratio": "70/30"
  }
  ```

### 3. Launch the Bot

- Run:

  ```bash
  python main.py
  ```

- Enter the Telegram code sent to your phone (one-time setup).

- Ensure MT5 is open and logged in.

- The bot starts monitoring your channel instantly!

---

## 🎮 Using the Bot – Client-Friendly Controls

Control everything from Telegram with ease!

### Inline Menu Buttons

- **Status**: View current settings and bot status.
- **Current Balance**: Check your MT5 account balance.
- **Set Risk %**: Adjust from 2% to 4% or customize.
- **Set Market Orders**: Choose 5, 10, 15, or custom.
- **Set Limit Orders**: Select 20, 30, 40, or custom.
- **Set Split Ratio**: Set 70/30, 50/50, or custom.
- **Reset Config**: Revert to default settings instantly.

### Commands

- `/startbot` – Start trading.
- `/stopbot` – Pause trading.
- `/status` – Check bot status.
- `/resetconfig` – Reset settings.
- `/setrisk 3` – Set 3% risk.
- `/setmarketorders 10` – Set 10 market orders.
- `/setlimitorders 30` – Set 30 limit orders.
- `/setsplit 70/30` – Set 70/30 split ratio.

---

## 🌐 Benefits for You

- **Save Time**: Automates trade execution, letting you focus on strategy.
- **Minimize Risk**: Protects your capital with smart lot sizing.
- **Full Control**: Customize settings to fit your style.
- **24/7 Trading**: Runs on VPS or always-on PC for non-stop action.
- **Expert Support**: I’m here to assist with setup and optimization!

---

## 💡 Ready to Boost Your Trading?

This bot is perfect for trading gold (XAUUSD) or other instruments you specify. I’ve built it with love and expertise, and I’m ready to tailor it to your needs. **Place an order today** and let’s take your trading to the next level!

### How to Order

- **Contact Me**: Reach out via Fiverr or email: kaleemullahchanna786@gmail.com.
- **Custom Quote**: I’ll provide a personalized plan based on your requirements.
- **Delivery**: Expect a fully functional bot in 4-7 days, with a demo and support included.

### What Clients Say

*"Amazing work! The bot saved me hours and boosted my profits. Highly recommend!"* – Satisfied Client\
*"Fast, reliable, and easy to use. Best decision I made!"* – Happy Trader

---

## 🔒 Security & Reliability

- Your credentials stay secure, stored locally on your device.
- Designed for privacy—only you control the bot.
- Regular updates ensure peak performance.

---

## 📢 Stay Connected

Follow my GitHub for updates or join my Telegram community for tips and support. Let’s build your trading success together!

*Last Updated: July 18, 2025*
