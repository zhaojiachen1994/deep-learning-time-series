# Awesome papers 
About time series anomaly detection, prediction
About recurrent neural network, LSTM

## [Table of Contents]()
* [Survey](#Survey)
* [Papers](#Papers)

## Survey


## Papers
- 20191119 `JICAI2019` [Outlier Detection for Time Series with Recurrent Autoencoder Ensembles](https://www.ijcai.org/proceedings/2019/0378.pdf) 
  - the first proposeal for using recurrent neural network autoencoder ensembles for outlier detection for time series.
  - autoencoder ensembles: 每个encoder随机缺少权重连接，最后在集成多个encoder,避免过拟合。
  - sparsely-connecected RNNs:随机连接当前时刻之前的几步，再进行集成。
