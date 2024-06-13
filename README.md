The main objective of this repository is to design a Long Short-Term Memory (LSTM) neural network which predicts stock pattern using TensorFlow. Hence leading to familiarize myself with the workings of aforementioned resources.

*LSTM* networks are a type of Recurrent Neural Network (RNN) specially designed to remember and process sequences of data over long periods. What sets LSTMs apart from traditional RNNs is their ability to preserve information for long durations, courtesy of their unique structure comprising three gates: the input, forget, and output gates. These gates collaboratively manage the flow of information, deciding what to retain and what to discard, thereby mitigating the issue of vanishing gradients — a common problem in standard RNNs. The amalgamation of LSTM with attention mechanisms creates a robust model for financial pattern prediction. The financial market is a complex adaptive system, influenced by a multitude of factors and exhibiting non-linear characteristics. Traditional models often fall short in capturing this complexity. However, LSTM networks, especially when combined with an attention mechanism, are adept at unraveling these patterns, offering a deeper understanding and more accurate forecasts of future stock movements.

APPLE stock was used as the preferred dataset for this simulation. Yahoo Finance was the choice for the source of the dataset with the help of *yfinance* library in Python.

*TensorFlow* and *Keras* were used as the tools to implement a LSTM network with an attention mechanism for stock price prediction. 

