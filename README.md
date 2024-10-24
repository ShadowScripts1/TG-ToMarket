> [<img src="https://img.shields.io/badge/Telegram-%40Me-orange">](https://t.me/roddyfred)

![img1](./.github/image/hero.png)

# Use Node.Js 18 or greater

## Functionality

| Functional                                                    | Supported |
| ------------------------------------------------------------- | :-------: |
| Claiming daily reward                                         |    ✅     |
| Claiming Farming reward                                       |    ✅     |
| Claiming tasks                                                |    ✅     |
| Starting Farming                                              |    ✅     |
| Playing games                                                 |    ✅     |
| Multithreading                                                |    ✅     |
| Binding a proxy to a session                                  |    ✅     |
| Auto-purchase of items if you have coins (multitap, attempts) |    ✅     |
| Binding a proxy to a session/query_id                         |    ✅     |
| Random sleep time between clicks                              |    ✅     |


## [Settings](https://github.com/ShadowScripts1/TG-ToMarket/blob/main/.env-example)

| Settings                       | Description                                                                |
| ------------------------------ | -------------------------------------------------------------------------- |
| **API_ID / API_HASH**          | Platform data from which to launch a Telegram session (stock - Android)    |
| **AUTO_PLAY_GAME**             | Whether the bot play the games (True / False)                              |
| **AUTO_CLAIM_DAILY_REWARD**    | Whether the bot should claim the daily rewards (True / False)              |
| **AUTO_FARM**                  | Whether the bot should start and claim farming (True / False)              |
| **AUTO_TASKS**                 | Whether the bot should claim tasks (True / False)                          |
| **AUTO_CLAIM_STARTS**          | Whether the bot should claim stars (True / False)                          |
| **AUTO_CLAIM_COMBO**           | Whether the bot should claim combo (True / False)                          |
| **SLEEP_BETWEEN_TAP**          | Delay between taps in seconds (eg. 70)                                     |
| **DELAY_BETWEEN_STARTING_BOT** | Delay between starting in seconds (eg. [20, 30])                           |
| **USE_PROXY_FROM_JS_FILE**     | Whether to use proxy from the `bot/config/proxies.js` file (True / False)  |
| **USE_PROXY_FROM_TXT_FILE**    | Whether to use proxy from the `bot/config/proxies.txt` file (True / False) |

## Installation

You can download [**Repository**](https://github.com/ShadowScripts1/TG-ToMarket) by cloning it to your system and installing the necessary dependencies:

```shell
~ >>> git clone https://github.com/ShadowScripts1/TG-ToMarket
~ >>> cd TG-ToMarket

#Linux and MocOS
~/TG-ToMarket >>> chmod +x check_node.sh
~/TG-ToMarket >>> ./check_node.sh

OR

~/TG-ToMarket >>> npm install
~/TG-ToMarket >>> cp .env-example .env
~/TG-ToMarket >>> nano .env # Here you must specify your API_ID and API_HASH , the rest is taken by default
~/TG-ToMarket >>> node index.js

#Windows
1. Double click on INSTALL.bat in TG-ToMarket directory to install the dependencies
2. Double click on START.bat in TG-ToMarket directory to start the bot

OR

~/TG-ToMarket >>> npm install
~/TG-ToMarket >>> cp .env-example .env
~/TG-ToMarket >>> # Specify your API_ID and API_HASH, the rest is taken by default
~/TG-ToMarket >>> node index.js
```

Also for quick launch you can use arguments, for example:

```shell
~/TG-ToMarket >>> node index.js --action=1

OR

~/TG-ToMarket >>> node index.js --action=2

#1 - Create session
#2 - Run clicker
```
