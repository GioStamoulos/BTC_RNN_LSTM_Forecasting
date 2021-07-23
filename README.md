# RNN_LSTM_BTC_PREDICTION
**Short Description**  
Two different RNN and two LSTM architectures were trained with bitcoin historical data (time series). The deep reccurent models were trained to take as input specific number of days-values of BTC-USD and gave as output the next day value of BTC-USD. Models were trained in different sizes of time window (number of input days-values) and more speciffically for 20, 30 & 50 days-values. The main goal is to predict after models' training and testing, the 10 future days-values of BTC-USD.  
**RNN**    
A recurrent neural network (RNN) is a class of artificial neural networks where connections between nodes form a directed graph along a temporal sequence. This allows it to exhibit temporal dynamic behavior. Derived from feedforward neural networks, RNNs can use their internal state (memory) to process variable length sequences of inputs. [1], [2] & [3]   
**LSTM**    
Long short-term memory (LSTM) is an artificial recurrent neural network (RNN) architecture[4] used in the field of deep learning. Unlike standard feedforward neural networks, LSTM has feedback connections.     
**Dataset**     
Bitcoin historical Data is publicly available and were downloaded from [5].  
Train data --> 90%  
Evaluate data --> 5%  
Test data --> 5%  

[1]     Dupond, Samuel (2019). "A thorough review on the current advance of neural network structures". Annual Reviews in Control. 14: 200–230.  
[2]     Abiodun, Oludare Isaac; Jantan, Aman; Omolara, Abiodun Esther; Dada, Kemi Victoria; Mohamed, Nachaat Abdelatif; Arshad, Humaira (2018-11-01). "State-of-the-art in artificial neural network applications: A survey". Heliyon. 4 (11): e00938. doi:10.1016/j.heliyon.2018.e00938. ISSN 2405-8440. PMC 6260436. PMID 30519653.  
[3]     Tealab, Ahmed (2018-12-01). "Time series forecasting using artificial neural networks methodologies: A systematic review". Future Computing and Informatics Journal. 3 (2): 334–340. doi:10.1016/j.fcij.2018.10.003. ISSN 2314-7288.  
[4]     Sepp Hochreiter; Jürgen Schmidhuber (1997). "Long short-term memory". Neural Computation. 9 (8): 1735–1780. doi:10.1162/neco.1997.9.8.1735. PMID 9377276. S2CID 1915014.  
[5] https://www.kaggle.com/mczielinski/bitcoin-historical-data 
