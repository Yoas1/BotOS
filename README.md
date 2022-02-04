# Bot-OS
## Create a new telegram-bot ##
**1** - Search Botfather in telegram.
**2** - Send command /newbot to Botfather.
**3** - Give the Telegram bot a name.
**4** - Give the Telegram bot a unique username, it must end in "bot".
**5** - Save the Telegram bot's access token, we will use it later in the configuration file "env.yml".

## Qbittorrent
**1** - Install Qbittorrent.
**2** - Set Qubittorrent Web UI:
      - Tools --> Preferences --> Web UI.
      - Enable Web User Interface (Remote control).
      - IP address = 0 and Port = 8080.
      - Set Username and Password.
      - Click Applay and OK.

## Download env.yml from Git
**1** - Download env.yml file from: [Download](https://github.com/Yoas1/BotOS).
**2** - Edit the env.yml file, instructions are in the file.
**3** - Save the env.yml file in the docker volume directory.
**5** - After the bot runs, you can edit it anytime and send it to the bot.

## Docker
**1** - Pull the BotOS image: **__docker pull yoas1/bot-os__**
**2** - Start the bot with auto-start in boot: dockr run -d -v <docker_volume_path>:/home/Donloads --restart=always yoas1/bot-os

# Now start use your bot :)
## More features will be added!
