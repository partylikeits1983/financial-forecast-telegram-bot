# Financial Prediction Telegram Bot
#### a bot that uses tensorflow and facebook prophet arima models to give you updates on stocks 

## Features
- quickly see ML predictions for cryptos and stocks
- get sent US treasury yield curves daily
- view 30 day and 180 day matricies on your phone 
- quickly identify broader market trends 
- make more informed trading decisions 

This bot was created to automate many of the more time consuming aspects of time series analysis using machine learning. Instead of having to have your computer to view charts, you can now just have them sent to you on telegram. 

You will need a dedicated vm or computer to run this telegram bot, ideally with x86 architecture. Pystan, a dependency for prophet, will fail to build on ARM-architecture. 

## Screenshots:

| | | 
|:-------------------------:|:-------------------------:|
|![](screenshots/screenshot1.png)|![](screenshots/screenshot2.png)|
|![](screenshots/screenshot3.png)|![](screenshots/screenshot4.png)|


### Installation:

To run, install all dependencies, change paths in python files for your machine, then execute:

```sh
python3 main.py
```

To automatically update models run:

```sh
python3 automate.py
```

The version of this bot is up and running at: 


If you like this bot, please consider buying me a coffee :)

Ethereum Address:  0x5c13Af2fbA82981994b1B3D5C20F7E2c971f28D3

## License
MIT
