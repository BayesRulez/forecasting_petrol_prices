# forecasting_petrol_prices
 
Over the past few years we have witnessed a number of significant global political and macroeconomic events. In my work I have frequently come across time series which show markedly different behaviour pre 2020 to post 2020. Disruption and change are the forecaster's enemy.

In this notebook I attempt to forecast the price of petrol at the pump (in the UK) eight weeks ahead.

As a secondary objective, I am curious as to the ability of modern, deep learning methods to compete with traditional, statistical models in predicting a volatile time series. In 2017 Makridakis et al published a paper titled Statistical and Machine Learning forecasting methods: Concerns and ways forward (https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0194889) in which they observed that traditional time series methods frequently still worked better than deep learning methods. At the time I followed this up carefully and broadly corroborated the claims. I was curious to try again using a modern method like Amazon's DeepAR model (https://arxiv.org/abs/1704.04110) or Google's Temporal Fusion Transformer (https://arxiv.org/abs/1912.09363) and compare it to some traditional, statistical methods.
