# huobi-historical-data

[中文](./README_CN.md)

1min intervals historical-data (OHLCV) from 2017/10/20 for  Encrypted Digital Currency on the exchange Huobi. 
include coins: btc、 eth、 etc、 ht、 xrp、 ltc、 bch、 bsv、 eos、 link etc. 

include currency pairs ： btcusdt 

ethusdt htusdt xrpusdt ltcusdt bchusdt eosusdt etcusdt bsvusdt

ethbtc htbtc xrpbtc ltcbtc bchbtc eosbtc etcbtc bsvbtc

## Summary
[kaggle](https://www.kaggle.com/mczielinski/bitcoin-historical-data) collect bitcoin history-data (OHLCV) on exchage **bitstamp** , but the data is no longer updated. 

On the one hand, view researches on kaggle, on the other hand, try to finding some interesting appearances in the field of encryption digital currency with strong randomness.

Coins: btc、 eth、 etc、 ht、 xrp、 ltc、 bch、 bsv、 eos、 link etc.

These data sources will be updated incrementally once a month.

## DataSource

[huobi](https://www.huobi.io)

[huobi sdk](https://huobiapi.github.io/docs/)

## Data Format

|     id     |     open     |     high     |     low     |     close     |     vol     |     count     |     amount     |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
|     id（seconds）     |     open price     |     highest price     |     lowest price     |     close price     |     volume     |     count num     |     amount: sum(price*count)     |


## Relate Project

[BitcoinPriceHistoryInChina](https://github.com/speculatecat/BitcoinPriceHistoryInChina) Huobi Historical data (daily price for btc and ltc) before october 2017

[cctx](https://github.com/ccxt/ccxt)

[kaggle](https://www.kaggle.com/mczielinski/bitcoin-historical-data) historical bitcoin market data at 1-min intervals
 **coinbaseUSD1-mindata2014-12-01to_2019-01-09.csv** and **bitstampUSD1-mindata2012-01-01to_2019-08-12.csv** , CSV files for select bitcoin + bitstamp exchanges for the time period of Jan 2012 to August 2019
 
[Bitfinex-historical-data](https://github.com/Zombie-3000/Bitfinex-historical-data)

**BTC/USD**(2013-2019)

**ETH/USD**(2016-2019)

**EOS/USD**(2017-2019)

**LTC/USD**(2013-2019)

**XRP/USD**(2017-2019)

**IOT/USD**(2017-2019)

**NEO/USD**(2017-2019)
