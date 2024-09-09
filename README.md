```markdown
# 🎌 Crunchyroll Account Checker Bot 🎌

This Python-based Telegram bot allows users to check Crunchyroll account credentials and categorize them as **Good**, **Premium**, **Bad**, or **Blocked**. The bot notifies admins via Telegram with detailed information on each account and provides a summary of the checking process.

## ✨ Features
- 🔐 **Account Credential Checker**: Verifies Crunchyroll accounts based on credentials provided.
- 🏆 **Account Categorization**:
  - **Good**: 🎉 Valid and functional accounts.
  - **Premium**: 🥇 Premium Crunchyroll subscription accounts.
  - **Bad**: ❌ Invalid credentials.
  - **Blocked**: 🚫 Blocked accounts.
- 🔄 **Real-time Summary**: Get a live summary of the total accounts processed with real-time updates.
- 📬 **Telegram Notifications**: Sends results to the owner in the following format:

## 🚀 Setup & Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/noobpiratexd/crunchy
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Edit the bot configuration:
   - Add your **Telegram bot token** and **Owner Chat ID** in the bot script.

4. Run the bot:
   ```bash
   python bot.py
   ```

## 🛠 How It Works

1. Users send a `.txt` file containing `user:pass` pairs to the bot.
2. The bot checks each account via the Crunchyroll API.
3. Results are categorized and sent back to the owner, including a real-time summary of:
   - 🎯 Total accounts processed.
   - 🥇 Premium accounts.
   - 🎉 Good accounts.
   - 🚫 Blocked and ❌ Bad accounts.

## 📋 Requirements

- Python 3.6+
- `telebot`, `requests` libraries

## 💡 Notes

- This bot checks for valid Crunchyroll credentials in bulk.
- Make sure to provide correct credentials and ensure compliance with platform policies.

## 📞 Support

If you encounter any issues or need assistance, feel free to reach out via Telegram: [@yourusername](https://t.me/yourusername)
