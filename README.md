# TradingBot
This is an AI trading bot that uses the news to predict buyer sentiment and place trades based off of that.
The bot uses the Alpaca paper trading API to do all of the trades.
I used finbert NLP model and transformer/pytorch/tokeniziers to predict sentiment as a tensor.
Here is an example of an output tensor: tensor(0.9979, grad_fn=<SelectBackward0>) negative False
I used conda virtual environments to make the project so to start it create a virtual environment in python 3.10
The tearsheet is in html so to view it you have to run the code alone but the stats are summarizied briefly below:

Starting Cash: 100k, Peak Cash: around 500k, Ending Cash: 450k, Net profit: 350k, Time: 3 years backtest

*Do not be startled by the HTML amount, it is because of the tearsheet website*
in order to activate the bot to trade on the real market add these lines at the end:
#trader = Trader()
#trader.add_strategy(strategy)
#trader.run_all()
