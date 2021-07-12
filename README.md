# RNN_LSTM_BTC_PREDICTION
**Short Description**  
2 different RNN and 2 LSTM architectures were trained with bitcoin historical data (time series). The deep reccurent models were trained to take as input specific number of days-values of BTC-USD and gave as output the next day value of BTC-USD. Models were trained in different sizes of time window (number of input days-values) and more speciffically for 20, 30 & 50 days-values.  
**RNN**  
A recurrent neural network (RNN) is a class of artificial neural networks where connections between nodes form a directed graph along a temporal sequence. This allows it to exhibit temporal dynamic behavior. Derived from feedforward neural networks, RNNs can use their internal state (memory) to process variable length sequences of inputs. [Ahmed Tealab 2019]  
**LSTM**  
Long short-term memory (LSTM) is an artificial recurrent neural network (RNN) architecture[Hochreiter et.al. 1997] used in the field of deep learning. Unlike standard feedforward neural networks, LSTM has feedback connections.   
**Dataset**   
Bitcoin historical Data is publicly available and were downloaded from https://www.kaggle.com/mczielinski/bitcoin-historical-data.
