# NumberSequencePrediction
Predicting the missing number given the previous number sequence using LSTM on Keras

ToyLSTM.py is a toy LSTM model to learn simple number sequences consisting of four consecutive numbers. The goal is to predict the last number given the first three consecutive numbers.

Testing results were not good due to small training data. Prediction results below:

[ 9 10 11] --> 10
[39 40 41] --> 34 
[24 25 26] --> 25
[28 29 30] --> 25 
[16 17 18] --> 17 
[47 48 49] --> 41 
[30 31 32] --> 28 
[18 19 20] --> 17 
[42 43 44] --> 36
