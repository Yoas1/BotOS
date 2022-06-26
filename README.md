![](https://visitor-badge.glitch.me/badge?page_id=Yoas1.BotOs)
# Bot-OS
## Create a new telegram-bot ##
**1** - Search Botfather in telegram. <br />
**2** - Send command /newbot to Botfather. <br />
**3** - Give the Telegram bot a name. <br />
**4** - Give the Telegram bot a unique username, it must end in "bot". <br />
**5** - Save the Telegram bot's access token, we will use it later in the configuration file "env.yml". <br />


## Download env.yml from Git
**1** - Download env.yml file from: [Download](https://github.com/Yoas1/BotOS). <br />
**2** - Edit the env.yml file, instructions are in the file. <br />
**3** - Save the env.yml file in the <path_to_save_downloads>. <br />
**5** - After the bot runs, you can edit it anytime and send it to the bot. <br />


## Docker
**1** - Image Docker-hub site: [BotOS](https://hub.docker.com/r/yoas1/bot-os). <br />
**2** - Pull the BotOS image: **__docker pull yoas1/bot-os:2.1__** <br />
**3** - Start the bot with auto-start in boot: **docker run -d -v <path_to_save_downloads>:/home/Downloads -v <path_to_save_data>:/root/.local/share/data/qBittorrent/ -v <path_to_save_data>:/root/.config/qBittorrent/ -p 8080:8080 yoas1/botos:2.1**


## Qbityorrent
**1** - for mange qbittorrent go to [Qbittorrent](http://127.0.0.1:8080/). <br />
**2** - user=admin password=adminadmin


# Now start use your bot :)
## More features will be added!
