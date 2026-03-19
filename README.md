# Telegram MFY Bot

Minimal repo for Render deployment. Polling + health-check endpoint (/) for uptime pinger.

## Run locally

`ash
pip install -r requirements.txt
BOT_TOKEN=your_token_here python bot.py
`

## Render
- Add env var BOT_TOKEN.
- Python version: set untime.txt to python-3.12.7 (Render reads it automatically).
- Start command: python bot.py.
- No build command needed.
- Uptime ping: https://<your-app>.onrender.com/

