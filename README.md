# Music-bot

A complete code to download for a music bot 🎧

Looking for a code for a music bot ? This fully open source code is made for your project !

If you need help with this project, to get support faster you can join the help server by just clicking [here](https://discord.gg/5cGSYV8ZZj).

*If you don't have any development knowledge, it is recommended to join the Discord support server to get help.*

### ⚡ Configuration

Open the configuration file located in the main folder `config.json`.

```json
{
    "app": {
        "prefix": "XXX",
        "token": "XXX",
        "playing": "by Zerio ❤️"
    },

    "opt": {
        "DJ": {
            "enabled": false,
            "roleName": "DJ",
            "commands": ["back", "clear", "filter", "loop", "pause", "resume", "seek", "shuffle", "skip", "stop", "volume"]
        },
        "maxVol": 100,
        "discordPlayer": {}
    }
}
```

Basic configuration

- `app/prefix`, the prefix that will be set to use the bot
- `app/token`, the token of the bot available on the [Discord Developers](https://discordapp.com/developers/applications) section
- `app/playing`, the activity of the bot

DJ mode configuration

- `opt/DJ/enabled`, whether the DJ mode should be activated or not 
- `opt/DJ/roleName`, the name of the DJ role to be used
- `opt/DJ/commands`, the list of commands limited to members with the DJ role

Advanced configuration

- `opt/maxVol`, the maximum volume that users can define
- `opt/discordPlayer`, options used by discord-player

### 📑 Installation

To use the project correctly you will need some tools.

[FFmpeg](https://www.ffmpeg.org) to process audio

[Node JS](https://nodejs.org/en/) (v16) for environment

Without forgetting of course the code editor ^^

You will also need to turn on Server Members Intent in the Discord Developer Portal.
![Example of Server Members Intent enabled](https://cdn.discordapp.com/attachments/889887818199998516/891131572605038622/unknown.png)

Realized with ❤️ by [ZerioDev](https://github.com/ZerioDev).

Please do not withdraw the license and keep the credits on this project.

To have full access to the project and to be able to withdraw the credits a small donation is accepted. 
