# telegram-testpointscore
A simple Telegram bot that can keep a score in a group.
A public instance is running here: https://t.me/keeping_score_bot

## How To Use
1. Add the bot to your group.
2. Type '/start'.
3. Type '/help' for more info.

## Running manually
1. Run `npm install`
2. Set environment variable `BOT_TOKEN`
3. Run `node app`

## Docker
### Building
`docker build -t 

### docker-compose
1. Edit docker-compose.yml and add Telegram bot token
2. `docker-compose build`
3. `docker-compose run -d`
