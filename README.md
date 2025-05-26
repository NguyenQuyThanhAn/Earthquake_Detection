# Earthquake_Detection using Deep Learning
The goal of this project was to train and and deploy a deep learning model to classify seismic signals into two categories - _earthquake_ or _noise_, and to predict earthquake characteristics such as earthquake magnitude, P-wave arrival time, and S-wave arrival time. Two ML models were trained and evaluated:
1) A convolutional neural network (CNN) model, trained on spectrogram images of the seismic signals
2) A long-short term memory (LSTM) model, a type of recurrent neural network, trained on computed seismic signal envelopes
# This repo consists of 6 directories:
## 1.Data demonstration
Contains csv file of training data and pictures that represent data characteristics such as magnitude, p-wave and s-wave sample time, ...
## 2.Trained results
Contains results after training of 2 models: CNN and LSTM and another proposed improved CNN model
## 3.earthquake detection
Contains 3 python files that will be imported in notebook files later on.
1) data_preprocessing.py: Contains functions used for pre processing input data before loading it into DL model
2) architectures.py: Contains functions used for determining DL models architecture
3) training ultis.py: Contains functions used for splitting dataset, plotting and validating training results
## 4.notebooks
Contains .ipynb files used for pre processing data, examining data, and train CNN and LSTM model
## 5.test_trained_model
Contains .ipynb files used for testing trained models with different dataset
## 6.Models
Contains link to drive that contain models

# Further details will be explained in attached report
