![](https://visitor-badge.glitch.me/badge?page_id=Yoas1.BotOs)
# Bot-OS
## Create a new telegram-bot ##
**1** - Search Botfather in telegram. <br />
**2** - Send command /newbot to Botfather. <br />
**3** - Give the Telegram bot a name. <br />
**4** - Give the Telegram bot a unique username, it must end in "bot". <br />
**5** - Save the Telegram bot's access token, we will use it later in the configuration file "env.yml". <br />

## Qbittorrent
**1** - Install Qbittorrent. <br />
**2** - Set Qubittorrent Web UI: <br />
  - Tools --> Preferences --> Web UI. <br />
  - Enable Web User Interface (Remote control). <br />
  - IP address = 0 and Port = 8080. <br />
  - Set Username and Password. <br />
  - Click Applay and OK. <br />

## Download env.yml from Git
**1** - Download env.yml file from: [Download](https://github.com/Yoas1/BotOS). <br />
**2** - Edit the env.yml file, instructions are in the file. <br />
**3** - Save the env.yml file in the docker volume directory. <br />
**5** - After the bot runs, you can edit it anytime and send it to the bot. <br />

## Docker
**1** - Image Docker-hub site: [BotOS](https://hub.docker.com/r/yoas1/bot-os). <br />
**2** - Pull the BotOS image: **__docker pull yoas1/bot-os__** <br />
**3** - Start the bot with auto-start in boot: **dockr run -d -v <docker_volume_path>:/home/Donloads --restart=always yoas1/bot-os**

# Now start use your bot :)
## More features will be added!
