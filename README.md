# Human Activity Recognition (HAR) using smartphones dataset and an LSTM RNN. 
By using LSTM RNN networks we were able to classify human movement amongst six categories:

WALKING,
WALKING_UPSTAIRS,
WALKING_DOWNSTAIRS,
SITTING,
STANDING,
LAYING.

The dataset was collected from 30 persons(referred as subjects in this dataset), performing different activities with a smartphone to their waists. The data is recorded with the help of sensors (accelerometer and Gyroscope) in that smartphone. This experiment was video recorded to label the data manually.

# Results
We were able to achieve an accuracy of 95%. The loss value measured is 0.1142
![Alt text](https://github.com/marcusnk237/lstm_har/blob/main/report.jpg)

# References:
The dataset can be found on the UCI Machine Learning Repository : https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013

The code was partially inspired by https://github.com/guillaume-chevalier/LSTM-Human-Activity-Recognition
