# Algorithmic-Trading
The examination of various algorithmic trading models reveals unique performance attributes for each method. The Genetic Algorithm (GA) shows a strong ability to optimize the weights of technical indicators, resulting in a trading strategy that yields the highest final portfolio value, but with some volatility. 

Although Genetic Programming (GP) emphasizes the predictive ability of simple lagged price values—specifically, the previous day’s closing price—it faces challenges in delivering consistent returns, highlighting its limitations in capturing more complex market behaviors. 

The Long Short-Term Memory (LSTM) network, an advanced type of recurrent neural network, presents significant volatility but also achieves a robust final portfolio value, indicating its capability to realize substantial gains at a higher risk. 

The Gated Recurrent Unit (GRU) model largely reflects the performance of the LSTM, exhibiting comparable volatility and a strong final portfolio value, thus highlighting the effectiveness of gated recurrent architectures for this purpose. 

In comparison, the Vanilla Recurrent Neural Network (RNN), which is the simplest version of recurrent networks, shows moderate volatility and a lower final portfolio value relative to LSTM and GRU, suggesting that more intricate architectures offer advantages in this trading context.

Ultimately, the selection of the most appropriate model hinges on the trader’s risk appetite and investment goals, with both evolutionary algorithms and sophisticated recurrent networks proving their potential for algorithmic trading, though with varying strengths and weaknesses.
