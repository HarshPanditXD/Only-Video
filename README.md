# VCPlayerBot

## Recommended Optional Vars

1. `DATABASE_URI`: MongoDB database Url, get from [mongodb](https://cloud.mongodb.com). This is an optional var, but it is recomonded to use this to experiance the full features.
2. `HEROKU_API_KEY`: Your heroku api key. Get one from [here](https://dashboard.heroku.com/account/applications/authorizations/new)
3. `HEROKU_APP_NAME`: Your heroku apps name.
4. `FILTERS`: Filter the search for channel play. Channel play means you can play all the files in a purticular channel using /cplay command. Current filters are `video document` . For searching audio files use `video document audio` . for video only search , use `video` and so on.

### 


## Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Deploy to Railway
<p><a href=https://github.com/subinps/VCPlayerBot/issues/7> <img src="https://img.shields.io/badge/Deploy%20To%20Railway-blueviolet?style=for-the-badge&logo=railway" width="200""/></a></p>

 
## Deploy to VPS

```sh
git clone https://github.com/subinps/VCPlayerBot
cd VCPlayerBot
pip3 install -r requirements.txt
# <Create Variables appropriately (.env [optional])>
python3 main.py
```

## Features

- Playlist, queue.
- Zero downtime in playing.
- Supports Video Recording.
- Supports Scheduling voicechats.
- Cool UI for controling the player.
- Customizabe to audio or video.
- Custom quality for video chats.
- Supports Play from Youtube Playlist.
- Change VoiceChat title to current playing song name.
- Supports Live streaming from youtube
- Play from telegram file supported.
- Starts Radio after if no songs in playlist.
- Automatic restart even if heroku restarts. (Configurable)
- Support exporting and importing playlist.

### Note

[Note To A So Called Dev](https://telegram.dog/subin_works/203): 

Kanging this codes and and editing a few lines and releasing a V.x  or an [alpha](https://telegram.dog/subin_works/204), beta , gama branches of your repo wont make you a Developer.
Fork the repo and edit as per your needs.

## LICENSE

- [GNU General Public License](./LICENSE)


## CREDITS

- [Laky-64](https://github.com/Laky-64) for [py-tgcalls](https://github.com/pytgcalls/pytgcalls)
- [Dan](https://github.com/delivrance) for [Pyrogram](https://github.com/pyrogram/pyrogram)


