# Spatio-Temporal-Event-Prediction
This repository contains some practical examples for Spatio-Temporal event prediction that contains data exploration, three different way to solve the problem and summary report of this solutions.


## Requirements
Code is written with python 3 and to use the code, you need to first install the following python packages:

```Shell
pip install notebook
pip install pytorch
pip install pytorch-lightning
pip install hmmlearn
pip install matplotlib
```

## Contents

- [Data Exploration](Data_Exploration.ipynb)

  To get an idea of the data and understand we need to explore the data. This will also give us the information to guess some of the parameters of the models we want to use.

- [Prediction with HMMs](Prediction_with_HMM.ipynb)

  As a baseline solution using HMMs to learn the patterns and trying to predict is a must to get a sense of the performance of the employed algorithms.

- [Prediction with MLP](Prediction_with_MLP.ipynb)

  MLP models are the key architectures to use for prediction, regression, classification problems. So basic and effective.

- [Prediction with RNN](Prediction_with_RNN.ipynb)

  RNN models are enabling us to learn from sequences and in this case, the temporal nature of the data is can be understood with the help of these models. Specifically with the help of LSTMs as it's less prone to some drawbacks of the vanilla RNNs.
  
- [Summary Report](Spatiotemporal_Event_Prediction.pdf)
