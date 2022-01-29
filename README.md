
# CoinMarketCap and CoinGecko Listing Sniper Bot

## Requirements
* Telegram Account

## Installation

### Telegram Requirements
 * Join the "Coinmarketcap Fastest Alerts" and/or "CoinGecko Fastest Alerts" telegram channel. The bot is triggered by the "insider info" posts to these channels. The bot will only buy each token one time.
    - https://t.me/CMC_fastest_alerts
    - https://t.me/CG_fastest_alerts

### Configure the sniper bot
 - With all of my bots you can find pre-compiled binaries in the dist folder. You should be able to run this bot anywhere (even mobile) without worrying about other dependencies.
 - For this bot you need to make sure to have all accompanying files, these are for the Telegram API.
 - The binaries already have the Telegram API configured and are ready to go. It's against Telegram's terms of service to share these in plain text, so if you are building from source you will need to generate your own API creds.

- RENAME the "env.example" file to ".env" and edit it.
```
# Your APP ID From my.telegram.org *OPTIONAL IF USING PRECOMPILED VERSION*
APP_ID=
# Your APP HASH From my.telegram.org *OPTIONAL IF USING PRECOMPILED VERSION*
APP_HASH=
# Your wallet address
RECIPIENT=
# Your wallet's private key
PRIVATE_KEY=
# BSC node web socket address
BSC_NODE_WSS=wss://bsc-ws-node.nariox.org:443
# Gas limit for transaction
GASLIMIT="1000000"
# Gas price for transaction
GASPRICE="5"
# CoinGecko settings
COINGECKO=true
COINGECKO_PURCHASEAMOUNT="0.005"
# CoinMarketCap settings
COINMARKETCAP=true
COINMARKETCAP_PURCHASEAMOUNT="0.01"
# Run bot in whitelist only mode?
WHITELIST_ONLY=false
# Always buy whitelisted tokens?
WHITELIST_ALWAYS=true
WHITELIST_PURCHASEAMOUNT="0.05"
# Comma seperated list of tokens to whitelist
WHITELIST=
```

## Usage
Open the command prompt or terminal (depending on your OS) and change to the directory where you extracted the bot, then run `listingsniper`. 

The first time you run the bot, you will be prompted to login with a telegram account.

- On macOS and linux, you may have to make the bot executable `chmod +x listingsniper`

## Results

![wmj3aOvD](https://user-images.githubusercontent.com/94490774/145612452-8677f80a-7a64-43a7-bdab-f2963b11e116.png)
![DXIhckJJ](https://user-images.githubusercontent.com/94490774/145612467-cc5a57c2-52ec-42c9-9587-4c57b35f46f6.png)
![valk](https://user-images.githubusercontent.com/94490774/145612475-b4bda5d7-9800-4564-b66d-f9fcdedec0a2.png)
![luto3](https://user-images.githubusercontent.com/94490774/145612481-96621851-0291-4d2c-a233-0540990f8cf9.png)
![dcip3](https://user-images.githubusercontent.com/94490774/145612487-ba2a4eb7-93e4-47f5-bf23-3b1334d1f5e0.png)
![moonx2](https://user-images.githubusercontent.com/94490774/145612499-9e8e70c7-d37a-4e3e-8803-6a12084639ec.png)
![grm](https://user-images.githubusercontent.com/94490774/145612514-d9e2b02d-cc89-463f-a51e-62fce222bfd0.png)
![ronin](https://user-images.githubusercontent.com/94490774/145612522-30083831-ab44-4351-82fe-79eddd2c6f33.png)
![fdm](https://user-images.githubusercontent.com/94490774/145612531-72bbe990-8f45-4a81-8610-672c4e873530.png)
