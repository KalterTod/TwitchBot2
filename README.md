# TwitchBot2
In order to begin, ensure you have docker desktop setup for your respective environment.
Start [here](https://www.docker.com/get-started)

You will need to create a `.env` file in the root directory with the following fields:
    TMI_TOKEN=
    CLIENT_ID=
    BOT_NICK=
    BOT_PREFIX=!
    CHANNEL=

For information on how to set these up, please see the [Getting Tokens: OAUTH](https://dev.twitch.tv/docs/authentication/getting-tokens-oauth) docs on Twitch.

If you have the ability to run make commands, then use the following commands

`make build`
`make up`

If you can only run docker commands, then use the following instead:

`docker compose build`
`docker compuse up -d`

And that's it! You should now have a fully functioning Twitch chat bot. Feel free to edit `bot.py` and add whatever functionality you would like to. 

