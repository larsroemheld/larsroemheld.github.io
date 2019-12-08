---
name: Probabilistic Forecasting
tools: [pytorch, RNNs, time series]
image: ../assets/images/2019_deepcast.png
description: This project used state-of-the-art forecasting ideas to provide probabilistic, as well as counterfactual, forecasts of retail demand across thousands of products.
---

## Probabilistic, Counterfactual Forecasting
This project merges several ideas to allow forecasting future demand in an ecommerce setting. For stocking and logistics decisions, it is often not good enough to have *one* expected number of orders; decisions can be considerably improved with probabilistic distributions over possible outcomes. In addition, forecasts can be improved when business plans are incorporated: price changes, for example, should naturally shift the expected number of units sold.

I developed this side project as a proof of concept, with promising results. The main ideas used are (1) counterfactual inference using prior [elasticity estimates](2017-deepelast/), (2) [Exponential Smoothing](https://eng.uber.com/m4-forecasting-competition/), and (3) [Autoregressive Recurrent Networks](https://arxiv.org/abs/1704.04110).

Since this side project merges my (NDA'd) professional work at the time with my private research interests, code and documentation unfortunately are available only on request.
