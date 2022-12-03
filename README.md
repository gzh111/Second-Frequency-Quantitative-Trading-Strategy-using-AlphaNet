# Second-Frequency-Quantative-Trading-Strategy-using-AlphaNet

This project is an automated trading strategy using AlphaNet and Risk Parity. It achieves 249.6% annual return, 25.4% annual volatility and 9.877 sharpe ratio in the back-tracking time period.

## Folders:
output: the training loss and validation loss of 3 kinds of alpha nets

pred: the prediction of best alpha net in training, validation and test set

saved_model: all alpha nets of 10 stocks on training set

test: test set

train_valid: training and validation set

test_30/60/120: test set are divided into per 30/60/120 min as input

train_30/60/120: training set are divided into per 30/60/120 min as input

valid_30/60/120: validation set are divided into per 30/60/120 min as input

## ipynb:
alphanet_30/60/120_log(x+1): alpha nets based on 30/60/120 min as input

build_datasets_for_predict: slicing dataset into 30/60/120 min as input for predicting

build_datasets_for_training: slicing dataset into 30/60/120 min as input for training

metrics_calculator: metrics calculating code

pred_test/train/valid: predicting in test/training/validation set

profile_return_test/train/valid: profile return in test/training/validation set

Stock_data_helper: Data Crawler
