# tg-send
Send and receive files between your server and Telegram.

##Setup guide
Download `servilobot.js` and `package.json` and put them where you want to run them. Install nodejs. On your console, do `npm start` or `npm init` and then `npm install pm2 --save`.

Create your own secrets.json with a text like this:

    {
        "servilobot_token": "<your token here>"
    }

Save it in the same directory as the bot and you're ready to run.

Then, simply start the bot by doing `pm2 start servilobot.js`.
