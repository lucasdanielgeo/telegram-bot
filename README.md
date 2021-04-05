# Telegram-bot
A telegram bot developed with python, based on the tutorial [How to create a Telegram Bot in Python in under 10 minutes](https://www.codementor.io/@karandeepbatra/part-1-how-to-create-a-telegram-bot-in-python-in-under-10-minutes-19yfdv4wrq)

# User Guide Instalation

First, install the project dependencies in a virtual environment:

```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
```

Now, to protect the bot token, save your telegram token in a `.env` file, by running:

```shell
echo "SECRET_KEY=YOUR_TELEGRAM_TOKEN" >> .env
```
Then you can run the bot with:

```shell
python3 bot.py
```
