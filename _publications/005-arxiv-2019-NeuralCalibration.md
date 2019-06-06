---
title: "Towards reliable and fair probabilistic predictions: field-aware calibration with neural networks"
collection: publications
permalink: /publications/NeuralCalibration
excerpt: "Towards reliable and fair probabilistic predictions: field-aware calibration with neural networks" 
date: 2019-05-27
venue: "Working paper"
year: 2019
paperurl: https://arxiv.org/abs/1905.10713
authorlist: "Feiyang Pan, Xiang Ao, Pingzhong Tang, Min Lu, Dapeng Liu, Qing He"
citation: "Feiyang Pan, Xiang Ao, Pingzhong Tang, Min Lu, Dapeng Liu, Qing He.Towards reliable and fair probabilistic predictions: field-aware calibration with neural networks. arXiv preprint arXiv:1905.10713."
status: 'non'
---
**Abstract:**
In machine learning, it is observed that probabilistic predictions sometimes disagree with averaged actual outcomes on certain subsets of data. This is also known as miscalibration that is responsible for unreliability and unfairness of practical machine learning systems. 

In this paper, we put forward an evaluation metric for calibration, coined field-level calibration error, that measures bias in predictions over the input fields that the decision maker concerns. We show that existing calibration methods perform poorly under our new metric. Specifically, after learning a calibration mapping over the validation dataset, existing methods have limited improvements in our error metric and completely fail to improve other non-calibration metrics such as the AUC score. We propose Neural Calibration, a new calibration method, which learns to calibrate by making full use of all input information over the validation set. We test our method on five large-scale real-world datasets. The results show that Neural Calibration significantly improves against uncalibrated predictions in all well-known metrics such as the negative log-likelihood, the Brier score, the AUC score, as well as our proposed field-level calibration error.

**Download: [[PDF]](https://arxiv.org/abs/1905.10713)**
