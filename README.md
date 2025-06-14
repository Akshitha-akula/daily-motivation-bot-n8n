# daily-motivation-bot-n8n
n automated workflow that sends a daily motivational quote via Telegram using n8n
# Daily Motivation Bot (n8n + Telegram)

This workflow sends a random motivational quote to a Telegram user every morning at 8 AM.

## How it Works

1. **Schedule Trigger**: Runs daily at 8 AM
2. **HTTP Request**: Fetches a quote from [zenquotes.io](https://zenquotes.io)
3. **Telegram Node**: Sends the quote to the user

## How to Use

- Import the JSON into your own n8n setup
- Replace placeholders with your:
  - Telegram bot token
  - Chat ID

Happy automating! 🤖💬
