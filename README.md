<div align="center">
    <h1>SOLANA SNIPER BOT</h1>
</div>

<p align="center">
    <img src="https://img.shields.io/github/languages/top/KanaDevv/Solana-sniper-bot">
    <br>
</p>

Solana is a cutting-edge sniper bot with an extremely fast and efficient sniper system designed to instantly target and secure tokens on the Solana blockchain.

## Installation

- Download this repository

- Install Required Libraries

```sh
pip install -r requirements.txt
```

- Start Bot

```sh
python main.py
```

**Note: This project has been made for Python 3.11**

## Sniper Bot

In addition to the wide range of features that Solana Sniper Bot offers, you can also use it to notch coins. Please note that Sniper Bot may undergo changes as there may be unforeseen issues.

### How it works

The bot will send a GET request to [Solana] every second.

If there is an existing route for this token, then it will execute it.

Please note that only tokens with sufficient liquidity and on-chain metadata are listed in the API: min. 250$ liquidity and a bid/ask price impact of less than 30%.

Once these criteria are met, it will take a few minutes for the token to be automatically added.

### Add a token to snipe

- Token/Project name
- Token Address
- Amount ($) to buy
- Take Profit ($)
- Stop Loss ($)
- Slippage (%)

If token has a launch date:

- Month
- Day
- Hours
- Minutes

## Overwiev

https://github.com/user-attachments/assets/5cc58690-1ff4-44fd-a132-6cb8976bf664

## Watch token

You can monitor your trading position by simply selecting the desired token.

example:

![logo](https://github.com/user-attachments/assets/8ee1fe94-3337-41db-8013-1238fec00022)

### Edit tokens

You can modify token info as follow:

- Name
- Address
- Selected Wallet
- Buy Amount
- Take Profit
- Stop Loss
- Slippage
- Launch date
- Delete

# FAQ

### Where are my private keys?

Your private keys are stored in wallets.json.

### Is it possible to swap any tokens?

You can only swap tokens that are listed on API based on their criterias.

## Contributing

If you would like to contribute to the project, please leave a star on this repository.

## Disclaimer

Please note that I'm not responsible for any loss of funds, damages, or other libailities resulting from the use of this software or any associated services.
This tool is provided for educational purposes only and should not be used as financial advice, it is still in expiremental phase so use it at your own risk.

## License

This project is licensed under the MIT License. For more information, see the [LICENSE file](LICENSE).
