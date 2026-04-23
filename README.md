# Telegram Google Sheet Report Bot

This project is a Python bot that automatically reads data from a Google Sheet and sends a daily report to a Telegram chat.

## 🚀 Features
- Reads data from public Google Sheets (CSV format)
- Filters today's data only
- Calculates total income
- Groups data by person and region
- Sends automatic reports to Telegram every 3 minutes

## 🛠 Technologies Used
- Python
- Pandas
- Requests
- Telegram Bot API
- APScheduler

## 📊 How it works
1. The bot fetches data from Google Sheets
2. Converts and cleans the data
3. Filters rows by today's date
4. Calculates total sum and groups results
5. Sends formatted message to Telegram

## ⚙️ Setup
1. Add your Telegram Bot Token
2. Add your Chat ID
3. Add Google Sheet URL (public access required)

```python
TELEGRAM_TOKEN = "your_token"
CHAT_ID = "your_chat_id"
SHEET_URL = "your_sheet_url"
