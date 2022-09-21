# Channel Auto-Post Bot

Use the [usermode](https://github.com/xditya/ChannelAutoPost/tree/user) branch, if you want to forward messages without being an admin in the from channel.

This bot can send all new messages from one channel, directly to another channel (or group, just in case), without the forwarded tag!

## Setting up 
* First:
> `APP_ID` and `API_HASH` - Get it from my.telegram.org   
> `BOT_TOKEN` - Get it from [@BotFather](https://t.me/BotFather)   
> `FROM_CHANNEL` - The ID of the main channel from where posts have to be copied. (Use @chnlidbot to get it.)   
> `TO_CHANNEL` - The ID of the channel to which the posts are to be sent. (Use @chnlidbot to get it.)   
   
* Chose a platform to deploy on:
<details>

Add the above values to the environment vars and deploy the bot.
</details>
<details>
<summary>Local Deploys</summary>
<br>
- Clone the repo:   <code>git clone https://github.com/infotrackcom/AutoForwarder</code></br>
- Make a <code>.env</code> file in the root of the repo, like <a href="https://github.com/infotrackcom/AutoForwarder/blob/main/.env.sample">.env.sample</a> and fill in the values.</br>
- Use <code>python3 bot.py</code> to start the bot.</br>  
</details>

## Usage
Add the bot to both channels with admin permission, and thats it!
All new messages will be auto-posted!!

## How to create your own bot

If you want to create your own bot, fork this repo and use it as your source repository on Heroku. To do that, connect GitHub to Heroku and select the forked repo.


#### Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://www.heroku.com/deploy?template=https://github.com/infotrackcom/AutoForwarder)


## Useful links

### Heroku

* [Heroku: Getting started python](https://devcenter.heroku.com/articles/getting-started-with-python)
* [Configuration variables heroku](https://devcenter.heroku.com/articles/config-vars#managing-config-vars)
* [Heroku: Deploying with git](https://devcenter.heroku.com/articles/git)

### Telegram bots

* [Telegram Bot introduction](https://core.telegram.org/bots)
* [Telegram Bot API](https://core.telegram.org/bots/api)
