---
title: "Achieving Online Regression Performance of LSTMs with Simple RNNs"
collection: publications
permalink: /publications/sRNN
---
N. M. Vural, <b>F. Ilhan</b>, S. F. Yilmaz and S. S. Kozat, "Achieving Online Regression Performance of LSTMs with Simple RNNs", <i>IEEE Transactions on Neural Networks and Learning Systems</i>, 2020.

[[arXiv]](https://arxiv.org/abs/2005.08948)


## Abstract
<div style="text-align: justify">Recurrent Neural Networks (RNNs) are widely used for online regression due to their ability to generalize nonlinear temporal dependencies. As an RNN model, Long-Short-Term-Memory Networks (LSTMs) are commonly preferred in practice, as these networks are capable of learning long-term dependencies while avoiding the vanishing gradient problem. However, due to their large number of parameters, training LSTMs requires considerably longer training time compared to simple RNNs (SRNNs). In this paper, we achieve the online regression performance of LSTMs with SRNNs efficiently. To this end, we introduce a first-order training algorithm with a linear time complexity in the number of parameters. We show that when SRNNs are trained with our algorithm, they provide very similar regression performance with the LSTMs in two to three times shorter training time. We provide strong theoretical analysis to support our experimental results by providing regret bounds on the converge rate of our algorithm. Through an extensive set of experiments, we verify our theoretical work and demonstrate significant performance improvements of our algorithm with respect to LSTMs and the state-of-the-art training methods.</div>
