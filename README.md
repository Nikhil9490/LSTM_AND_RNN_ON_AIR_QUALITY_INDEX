# LSTM_AND_RNN_ON_AIR_QUALITY_INDEX

The dataset dealt with air quality measurememts and it included different 
kind of concentrations and factors affecting it. A few features are CO(GT), 
C6H6(GT) and PT08.S4(NO2). The data is sequential and is not supposed to 
be shuffled. I was asked to take PT08.S4(NO2) as my target label. These 
kinds of datasets are suitable for time series analysis. 

LSTM AND RNN are implemented. RNNs can capture sequential relationships and dependencies by sending information 
through hidden states. The problem with RNN is it does not work well  with long 
term dependencies due to vanishing gradient problem. 
LSTM improves over RNN with memory cells which allows them to capture both 
short and long term dependencies efficiently when working on time series data. 

RNN model successfully followed the trend of the data to a certain extent. The difference 
between lenghths of two graphs in LSTM is lower compared to RNN. LSTM’s performance is better because it successfully captured both short and long term 
dependencies better than RNN.
