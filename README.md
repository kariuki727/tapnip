# URL Shortner Telegram Bot 
Convert Any Shortner Link To Your With Post
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
* Any URL shortener with bulk post
* You can use with your short website API TOKEN
</p>

</p>
<h1 align="left">
  <b>Earn Money with Our Bot</b>
</h1>

### Telegram Bot [Tapnip Bot - Earn Money on Short Links](telegram.me/tapnip_bot)

## Deploy 

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/kariuki727/tapnip)

## Variables Required for Bot
* `API_ID` - Your Telegram API id
* `API_HASH` - Your Telegram API hash
* `BOT_TOKEN` - Your Telegram bot token from @BotFather
* `ADMINS` - Admins Telegram id (If you don't have admin then, enter owner id) 
* `DATABASE_NAME`- Your DB name. Default name 'my'
* `DATABASE_URL` - Your database url from MongoDB.com 
* `OWNER_ID` - Owner id from Telegram
* `LOG_CHANNEL` - Your Telegram logs Channels id
* `UPDATE_CHANNEL` - Your Telegram updates Channel user name without @ (for Force Subscription)
* `BROADCAST_AS_COPY` - Default value is 'True' ('True' if forward should be avoided)
* `WELCOME_IMAGE` - A welcome image when someone hit /start command
* `LINK_BYPASS` - Default value is 'False'

## Bot Commannds
* `start` - check bot alive
* `about` - details about bot
* `help` - get help
* `api` - set api token
* `footer` - set footer text

## How to Setup Your Shortener Base
In this code, Go to "[users.py](/database/users.py)" in database folder
#### Find and replace with your <b>Site Base</b>
```
base_site: tapnip.vip
```
  
## Credits 

* [![DK](https://img.shields.io/static/v1?label=DKBOTZ&message=Telegram&color=critical)](https://t.me/briceka)
* [![Contact](https://img.shields.io/static/v1?label=Contact&message=On+Telegram&color=critical)](https://t.me/briceka)
