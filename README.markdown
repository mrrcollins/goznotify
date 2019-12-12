# GozNotify

~~This is a commandline notify script that I currently use with [Faast App](http://faast.io/)~~

Faast has been replaced with a Telegram bot. 

# Setup

Your API key (for the bot) and your chat ID (where to send the message) needs to be stored in in ~/.goznotify. Example:

    APIKEY=xxxxxxxxxxxxx
    TO=xxxxxxx

The API key comes from the @BotFather, a bot on Telegram that creates Bots. To get your chat id to place in `TO`, send your bot a message and then visit:

    https://api.telegram.org/bot<yourtoken>/getUpdates

The JSON response will have an `id:` field, that's your chat id.
