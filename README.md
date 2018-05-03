# Bearbot

Bearbot is a general-purpose Discord bot written in [Discord.js](https://discord.js.org).

## Run your own instance of Bearbot

You will need the following:

* [Node.js](https://nodejs.org) (LTS or latest)
* NPM (this should come with Node.js)
* [Visual Studio Build Tools](https://aka.ms/BuildTools) (**THIS IS NEEDED ON WINDOWS.** Click the link or run `npm install --global --production windows-build-tools`)
* A spare Discord bot (make one [here](https://discordapp.com/developers/))
* [Git](https://git-scm.org) (to clone the repository and keep it up to date)

Do the following:

```shell
git clone https://github.com/plusreed/Bearbot
cd Bearbot
npm i
```

This will install all the dependencies. If you get an error, more than likely you do not have the build tools installed.

Fill in the example config (configs/bot/bearbot.example.json) with your details (your bot token, your user ID, prefix, etc.).

You'll also need `speedtest-cli` and `cat` (so, basically a Linux system).

Whenever you're ready, start up the bot with `npm run bot`.

You could also use something like `forever`, `pm2`, or `nodemon`.

## License

Licensed under the GNU AGPL 3.0.