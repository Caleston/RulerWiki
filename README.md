# RulerWiki

A discord bot for RulerCraft which tracks the server and shows many stats, allowing you to interact with the server from your discord

## Feature overview

- Get commands: get basic information for different objects on the server
- Compare commands: compare different nations, towns and players with each other. Supports up to 5 of each
- History commands: get historical information for players and towns
- Top commands: rank players, nations and towns by multiple different figures
- Distribution commands: rank towns within another nation by different attributes
- Notifications: get notified when someone enters your territory

## Commands

Too many to list here try the bot to see

# Installing and running

## Requirements

- Modules in requirements.txt
- Python 3.8+

## Set-up

- Create a file named `.env` with the following:
```
token="discord bot token"
webhook="a webhook to send to when the bot is added to a new server. if left blank will cause a non-fatal error when bot is added to server"
```
- Open setup.py
- Set refresh_commands to True
- Add your Discord ID to mods
- Ensure the bot profile has "server members intent" enabled on [discord developers](https://discord.com/developers)
- Config anything else in setup.py

## Running

- Run the `main.py` file to start the bot.
- After first run, make sure to set refresh_commands to False in `setup.py`
