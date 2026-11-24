# Meme Bot

Meme Bot is a Discord bot built with Python using the discord.py library. The bot fetches random memes from a public API and shares them in a Discord channel when requested by a user.

#Description

This project was created to learn Python programming, Discord bot development, and API integration. The bot listens for user commands and retrieves random memes from the Meme API.

When a user types the $meme command, the bot sends a request to the API, retrieves a random meme, and posts it in the Discord channel.
# DiscordBot

## Requeriments

You need to have Python installed. The project dependencies are listed in `requirements.txt`.

## Instalación

Open a terminal in the project folder and run:

```bash
py -m pip install -r requirements.txt
```

## Configuration and execution 

Configure your Discord token in `bot.py` ad execute the bot. DONT'T SHARE OR PUBLIR YOUR REAL TOKEN:

```bash
py bot.py
```


# Features
Fetches random memes from a public API
Responds to user commands
Sends meme images directly to Discord channels
Built with Python and discord.py
Easy to expand with new commands and features

# Available Commands
$meme

Retrieves and sends a random meme.

Example:

User: $meme

Bot: https://example-meme-url.com

# Technologies Used
Python 3
Discord.py
Requests
JSON
Meme API

#Installation
Clone the repository:

git clone https://github.com/Javilord53/meme-bot.git

Navigate to the project directory:

cd meme-bot

Install dependencies:

pip install discord.py requests

Replace the placeholder token in the code with your Discord bot token:

client.run("TOKEN HERE")

Run the bot:

python main.py

# How It Works

The bot uses the Meme API to retrieve random memes.

The get_meme() function sends an HTTP request to:

https://meme-api.com/gimme

The API returns data in JSON format. The bot extracts the image URL from the response and sends it to the Discord channel whenever the user enters the $meme command.

# Project Structure

meme-bot/

├── main.py
 ├── requirements.txt
 ├── .gitignore
 └── README.md
