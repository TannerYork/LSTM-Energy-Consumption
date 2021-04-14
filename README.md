# MTGNN-Energy-Consumption
This is a PyTorch implementation of a Graph Neural Net (GNN) for multivariable time-series forecasting for energy consumption and, as an eventual addition, solar energy production.

## Project Scope
This project will involve...
* learning Pytorch for model development and GNN for multivariable time-series forecasting
* learning GNN for multivariable time-series forecasting
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
|     Step      |     Goal      |
| ------------- | ------------- |
|   Step #1     | Understand better what [GNN](https://towardsdatascience.com/a-gentle-introduction-to-graph-neural-network-basics-deepwalk-and-graphsage-db5d540d50b3) are and how they can be implemented in a [familar framework](https://arxiv.org/pdf/2006.12138.pdf) |
|   Step #2     | Get familiar with PyTorch through the [Getting Started Guide](https://pytorch.org/tutorials/beginner/basics/intro.html)  |
|   Step #3     | Start building the GNN based on the papers above |
|   Step #4     | Finish building the GNN and work on evaluating and comparing to other [models](https://github.com/nnzhan/MTGNN) |
|   Step #5     | Write up the comparison of my optimized model vs. other models |
