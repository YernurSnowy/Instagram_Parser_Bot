# Instagram Bot

## Project Overview
This project features a Telegram bot that interacts with Instagram to fetch user data, managing rate limits and handling requests asynchronously. The bot provides functionalities like getting the list of followers for a given username.

## Features
- Fetch Instagram data via Instaloader.
- Asynchronous handling of requests to manage rate limits.
- Interaction with users through a Telegram bot interface.

## Prerequisites
- Python 3.x
- Aiogram
- Instaloader
- A Telegram Bot Token
- An Instagram account credentials

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YernurSnowy/Instagram_Parser_Bot
   ```
2. Install the required Python packages:
   ```bash
   pip install aiogram instaloader
   ```

## Configuration
Update the configuration details in `main.py`:
- Replace `YOUR_BOT_TOKEN` with your Telegram bot token.
- Update `YOUR_INSTAGRAM_USERNAME` and `YOUR_INSTAGRAM_PASSWORD` with your Instagram credentials.

## Usage
To run the bot, execute:
```bash
python main.py
```
The bot will start and can be interacted with through Telegram.


