---
title: "Markovian RNN: An Adaptive Time Series Prediction Network with HMM-based Switching for Nonstationary Environments"
collection: publications
permalink: /publications/mRNN
---
<b>F. Ilhan</b>, O. Karaahmetoglu and S. S. Kozat, "Markovian RNN: An Adaptive Time Series Prediction Network with HMM-based Switching for Nonstationary Environments", <i>IEEE Transactions on Neural Networks and Learning Systems</i>, 2020.
[[PDF]](https://arxiv.org/abs/2006.10119)


## Abstract
We investigate nonlinear regression for nonstationary sequential data. In most real-life applications such as business domains including finance, retail, energy and economy, timeseries data exhibits nonstationarity due to the temporally varying dynamics of the underlying system. We introduce a novel recurrent neural network (RNN) architecture, which adaptively switches between internal regimes in a Markovian way to model the nonstationary nature of the given data. Our model, Markovian RNN employs a hidden Markov model (HMM) for regime transitions, where each regime controls hidden state transitions of the recurrent cell independently. We jointly optimize the whole network in an end-to-end fashion. We demonstrate the significant performance gains compared to vanilla RNN and conventional methods such as Markov Switching ARIMA through an extensive set of experiments with synthetic and real-life datasets. We also interpret the inferred parameters and regime belief values to analyze the underlying dynamics of the given sequences.