# telegram-scorebot
A simple Telegram bot that can keep a score in a group.

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
`docker build -t telegram-scorebot .`

### docker-compose
1. Edit docker-compose.yml and add Telegram bot token
2. `docker-compose build`
3. `docker-compose run -d`
