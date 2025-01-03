# Validator Monitor Bot

A comprehensive Telegram bot for monitoring and managing blockchain validators with Tenderduty integration.

## Features

- Validator monitoring and alerts
- Network status tracking
- Performance analytics
- Automated node management
- Machine learning-based predictions
- Interactive Telegram interface

## Installation

1. Clone the repository:
```
git clone https://github.com/0xmtnslk/validator-monitor-bot.git
cd validator-monitor-bot
```

Install dependencies:

```
pip install -r requirements.txt
```

Configure the bot:
Copy config/bot_config.yml.example to config/bot_config.yml
Add your Telegram bot token and other configurations
Run the bot:

```
python src/main.py
```
Configuration
See configuration.md for detailed setup instructions.

Usage
See usage.md for detailed usage instructions.

License
MIT License


3. `.env.example`:
```env
# Telegram Bot Configuration
BOT_TOKEN=your_telegram_bot_token_here
ADMIN_USER_ID=your_telegram_user_id

# Database Configuration
DATABASE_URL=sqlite:///data/bot.db

# Tenderduty Configuration
TENDERDUTY_HOST=localhost
TENDERDUTY_PORT=8888

# RPC Configuration
PRIMARY_RPC_URL=http://your-primary-rpc:26657
BACKUP_RPC_URLS=http://backup1:26657,http://backup2:26657
