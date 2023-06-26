This docker-compose file is written with reference to the project [moe-sticker-bot](https://github.com/star-39/moe-sticker-bot) to facilitate users in managing with docker-compose.

Instructions for use are as follows:
1. Create bot with [BotFather](https://t.me/botfather)
2. Replace your Telegram bot token into docker-compose.yml.
3. Replace your bot name into docker-compose.yml.
4. Start with command:
```
docker-compose up -d
```
5. When update, execute this command:
```
docker-compose stop
docker-compose rm
docker-compose up -d
```
