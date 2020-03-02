# 火币历史交易数据
本项目致力于收集火币交易所上，从2017年10月20日器的**1min** 间隔级别的主要几种数字加密币的历史交易数据(OHLCV)。包括货币对： btcusdt ethusdt htusdt xrpusdt ltcusdt bchusdt eosusdt etcusdt bsvusdt

## 概述
[kaggle](https://www.kaggle.com/mczielinski/bitcoin-historical-data) 收集了**bitstamp** 和 **coinbase**交易所上2012--2019年期间的历史交易数据(OHLCV) , 这些数据目前已经不再更新. 

在学习Kaggle上的数据分析的基础上，本项目也试图持续收集类似的数据，并且期待发现在高度随机的加密数字货币交易方面一些有趣的现象。

收集的币种: btc ht eth etc ltc xrp bch eos etc。计价基准单位：usdt。

如果接口没有重大问题，本项目将每个月更新一次数据集.

## 数据源

[火币全球huobi](https://www.huobi.io)

[火币API](https://huobiapi.github.io/docs/)

## 数据格式

|     col0     |     col1     |     col2     |     col3     |     col4     |     col5     |     col6     |     col7     |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
|  Amount  |     Open    |    Close    |     High     | Secondid  |    Count    |     Low     |   Volume   |


## 相关项目

[cctx](https://github.com/ccxt/ccxt)

[kaggle](https://www.kaggle.com/mczielinski/bitcoin-historical-data) bitcoin历史市场数据 1min 间隔级别。
 **coinbaseUSD1-mindata2014-12-01to_2019-01-09.csv** 和 **bitstampUSD1-mindata2012-01-01to_2019-08-12.csv** 两个文件 , CSV 文件选择了**bitcoin** 和 **bitstamp** 两个老牌交易所2012年到2019年的数据

[BitcoinPriceHistoryInChina](https://github.com/speculatecat/BitcoinPriceHistoryInChina) 火币历史交易数据(2017年10月前的btc 和 ltc 每日数据)
