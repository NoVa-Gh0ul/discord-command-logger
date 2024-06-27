# discord-command-logger
Discord SelfBot that will log commands used in one server, and relay them to another

# Author

This was created by `shwp` on [Discord](https://discord.com/users/1014174658179899503)

Support his main Xbox-based Discord bot called Guh by [buying guh bot a coffee!](https://buymeacoffee.com/guh_bot)

# DISCLAIMER

This is a Discord SelfBot, which goes **against Discord ToS**. This software is provided to you to be used at your own discretion. 

# Setup

1. Make sure you have Node.js installed on your local machine (install here: https://nodejs.org/en/download/prebuilt-installer)

2. Clone this repository at https://github.com/NoVa-Gh0ul/discord-command-logger

3. Open the terminal and run `npm install`

4. Fill in required `config.json` values:
    - `token` (authorization for the bot)
    - `channel_id` (channel to log commands from)
    - `webhook_url` (webhook for where the logs are sent to)

Optional values will be listed further below

5. Run `node .`

Enjoy :D


# Config Info

Other optional values include:

- **status**: `dnd` | `idle` | `invisible` | `online`
- **device_spoof**: `pc` | `phone`
- **time**: *do not edit this*
- **embed_color**: support hex string values for colors
- **check_last_used_command**: `integer_value` (how long until it checks for the last used command in the set channel again)
