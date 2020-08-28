---
title: "Unsupervised Online Anomaly Detection On Irregularly Sampled Or Missing Valued Time-Series Data Using LSTM Networks"
collection: publications
permalink: /publications/UOAD
---
O. Karaahmetoglu, <b>F. Ilhan</b> and S. S. Kozat, "Unsupervised Online Anomaly Detection On Irregularly Sampled Or Missing Valued Time-Series Data Using LSTM Networks", <i>IEEE Transactions on Neural Networks and Learning Systems</i>, 2020.

[[PDF]](https://arxiv.org/abs/2005.12005)


## Abstract
We study anomaly detection and introduce an algorithm that processes variable length, irregularly sampled sequences or sequences with missing values. Our algorithm is fully unsupervised, however, can be readily extended to supervised or semisupervised cases when the anomaly labels are present as remarked throughout the paper. Our approach uses the Long Short Term Memory (LSTM) networks in order to extract temporal features and find the most relevant feature vectors for anomaly detection. We incorporate the sampling time information to our model by modulating the standard LSTM model with time modulation gates. After obtaining the most relevant features from the LSTM, we label the sequences using a Support Vector Data Descriptor (SVDD) model. We introduce a loss function and then jointly optimize the feature extraction and sequence processing mechanisms in an end-to-end manner. Through this joint optimization, the LSTM extracts the most relevant features for anomaly detection later to be used in the SVDD, hence completely removes the need for feature selection by expert knowledge. Furthermore, we provide a training algorithm for the online setup, where we optimize our model parameters with individual sequences as the new data arrives. Finally, on real-life datasets, we show that our model significantly outperforms the standard approaches thanks to its combination of LSTM with SVDD and joint optimization.