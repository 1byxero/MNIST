Dataset: MNIST digit recongnition
Note: the original dataset has been tweaked to meet the torch requirements. The labels of all training images with of digit '0' are changed to '10'

Learning Algorithm: Neural Network with Stochastic Gradient

Neural Network profile:
3 Layer network 
784 nodes at Input Layer
100 nodes at Hidden Layer
10 nodes at output Layer

Activation function: Sigmoid
Output function: LogSoftMax
Loss function: Negative Log Likelihood
Training Epoch: 5
Regularization: Not used

epoch 1 error = 1.7188340870454	
epoch 2 error = 1.5771125041969	
epoch 3 error = 1.6148196502816	
epoch 4 error = 1.4768090130265	
epoch 5 error = 1.3352091500041	

Final training error = 1.3352091500041	

Testset Accuracy = 64.08%
