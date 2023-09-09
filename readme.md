# An Artificial Neural Network to predict leakage amount in a Water Distribution Network
Let me present my bachelor thesis > Water leakage detection in a water distribution network using Artificial Neural Network

## Overview
An artificial neural network (ANN) made in Python using the machine learning library TensorFlow 2 and the Keras API that is built on top of TensorFlow. The aim of the ANN is to predict the number of existing leakages in a water distribution network (WDN) when taking different pressure data as
input. 

## Results and how it was done
To analyze the model's results, descriptive statistics were used, and the Root Mean Square Error
(RMSE) was calculated to 0.452. The results were able to discover a method for an ANN to detect pipe
leakage in a WDN using BattLeDIM 2020 dataset, but not how to localize them. The model built in this
study could be used to detect new leakages in a WDN by taking in new readings from pressure sensors
and outputting the number of leakages in the WDN. When the output is increased by one, the model
shows that a new leak has occurred.

## tbd
- graphs and tables
