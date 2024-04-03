# TradingBot
This is an AI trading bot that uses the news to predict buyer sentiment and place trades based off of that.
The bot uses the Alpaca paper trading API to do all of the trades.
I used finbert NLP model and transformer/pytorch/tokeniziers to predict sentiment as a tensor.
Here is an example of an output tensor: tensor(0.9979, grad_fn=<SelectBackward0>) negative False
I used conda virtual environments to make the project so to start it create a virtual environment in python 3.10
