# LSTM Energy Consumption
This project was originally meant for recreating the MTGNN model for time series forecasting but due to time constraints and deadlines, it's changed to exploring the LSTM model instead.

## Project Scope
This project will involve...
* understanding both multi and single-step time series analysis/forecasting.
* creating and optimizing a Long-Short Term Memory (LSTM) model using Keras.
* the energy consumption data from the multivariable time-series data frond [here](https://github.com/laiguokun/multivariate-time-series-data)

## Project Research
[Estimation of energy consumption in machine learning](https://www.sciencedirect.com/science/article/pii/S0743731518308773) <br>
This paper explains different approaches to solving the problem of estimating energy consumption for both the software and hardware level. These include performance counters (PMC), simulation, architecture or instruction level, and real-time estimation approaches.

[Modeling Long- and Short-Term Temporal Patterns with Deep Neural Networks](https://arxiv.org/abs/1703.07015) <br>
This paper proposes using a Long- and Short-term Time-series network (LSTNet) design that uses both Convolution Neural Network (CNN) and the Recurrent Neural Network (RNN). After testing and reviewing the data, they find that using this approach significantly improved the results.

[Machine learning approaches for predicting household transportation energy use](https://www.sciencedirect.com/science/article/pii/S2590252020300258) <br>
This paper presents four modeling techniques for predicting household transportation energy consumption by exploring decision trees, random forest, and neural networks in addition to elastic net regularization analyses. They find that the linear model has trouble with the non-linear inter-variable relationships, that straight Neural Nets (NN) is not the best because of the inability to provide feature important insights.

[Machine learning for estimation of building energy consumption and performance](https://viejournal.springeropen.com/articles/10.1186/s40327-018-0064-7) <br>
This paper provides a substantial review on the four main ML approaches including artificial neural network, support vector machine, Gaussian-based regressions, and clustering, which have commonly been applied in the forecasting and improving building energy performance. They find that not one network is better than the rest but that it depends on the nature of the given data.

[Multivariable Time-Series Forecasting Graph Neural Net (MTGNN)](https://github.com/nnzhan/MTGNN) <br>
This is a Pytorch implementation for the paper Connecting the Dots: Multivariate Time Series Forecasting with Graph Neural Networks mentioned above. This gives a good comparison for the model I will be building during this project.

## Project Plan
|   Milestone   |     Goal      |    Status     |
| ------------- | ------------- | :-----------: |
|  Milestone #1 | Research time series forecasting and LSTM model | ✅ |
|  Milestone #2 | Explore, visualize, and preprocess the data  | ✅ |
|  Milestone #3 | Build a variety of LSTM models for comparison and evaluation  | ✅ |
|  Milestone #5 | Tune model hyperparameters to create an optimized model | |
