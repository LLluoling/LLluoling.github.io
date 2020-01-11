---
title: "Field-aware calibration: a simple and empirically strong method for reliable probabilistic predictions"
collection: publications
permalink: /publications/calibration
excerpt: "Field-aware calibration: a simple and empirically strong method for reliable probabilistic predictions"
date: 2020-01-11
venue: "WWW"
year: 2020
paperurl: "https://arxiv.org/abs/1905.10713v2"
authorlist: "Feiyang Pan, Xiang Ao, Pingzhong Tang, Min Lu, Dapeng Liu, Lei Xiao and Qing He"
citation: "Feiyang Pan, Xiang Ao, Pingzhong Tang, Min Lu, Dapeng Liu, Lei Xiao and Qing He. 2020. Field-aware calibration: a simple and empirically strong method for reliable probabilistic predictions. In Proceedings of the 2020 World Wide Web Conference (WWW'19), May 13-17, 2019, San Francisco, CA, USA. ACM, New York, NY, USA, 11 pages. https://doi.org/10.1145/3308558.3313616"
status: 'acc'
---
**Abstract:**
It is often observed that the probabilistic predictions given by a machine learning system can disagree with averaged actual outcomes on specific subsets of data, which is also known as the issue of miscalibration. It is responsible for the unreliability of practical machine learning systems. For example, in an online advertising system, an ad can receive a click-through rate prediction of 0.1 over some population of users where its actual click rate is 0.15. In such cases, the probabilistic predictions have to be fixed before deployment.

In this paper, we first introduce an evaluation metric for calibration, coined field-level calibration error, that measures bias in predictions over the input fields that the decision-maker concerns. We show that existing post-hoc calibration methods have limited improvements in the new field-level metric and completely fail to improve other non-calibration metrics such as the AUC score. To this end, we propose Neural Calibration, a simple yet powerful post-hoc calibration method that learns to calibrate by making full use of the field-aware information over the validation set. We present extensive experiments on five large-scale datasets, including a default prediction dataset, an insurance dataset, and three user response prediction tasks for advertising. The results showed that Neural Calibration significantly improves against uncalibrated predictions in common metrics, including the negative log-likelihood, Brier score, AUC, as well as the field-level calibration error, and consistently outperforms existing methods.

**Download: [[PDF]](https://arxiv.org/abs/1905.10713v2)**
