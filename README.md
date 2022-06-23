# module_13_challenge
Challenge assignment for Module 13

This consists of three binary classification models using a deep learning neural network trained with data from companies funded by a venture capital firm.  The aim is to better predict whether startups given funding will end up successful based on various features of previously funded companies.  The neural networks for each of the three models differ slightly to try to find the best predictor.


# Required Libraries  

pandas

pathlib

TensorFlow

sklearn


# Model Results

Original Model Results
268/268 - 0s - loss: 0.5887 - accuracy: 0.7207 - 198ms/epoch - 738us/step
Loss: 0.5887470841407776, Accuracy: 0.7206997275352478

Alternative Model 1 Results
268/268 - 0s - loss: 0.5798 - accuracy: 0.7303 - 291ms/epoch - 1ms/step
Loss: 0.5797541737556458, Accuracy: 0.7302623987197876

Alternative Model 2 Results
268/268 - 0s - loss: 0.6087 - accuracy: 0.7304 - 260ms/epoch - 971us/step
Loss: 0.6087480187416077, Accuracy: 0.7303789854049683

Based on these results, model A1 would be the best model to choose, with lower loss and comparable accuracy to the others.