Dataset: [MNIST digit recognition](http://yann.lecun.com/exdb/mnist/) 
------------------------------------------------------------------------
Neural network for MNIST digit recognition implemented in [Torch7](http://torch.ch/)

Note: **This is outdated readme. It will soon be updated**

Note: the original dataset has been tweaked to meet the torch requirements. The labels of all training images of digit '0' are changed to '10'

###Learning Algorithm:
**Neural Network with Stochastic Gradient**


###Neural Network profile:

3 Layer network 

784 nodes at Input Layer

100 nodes at Hidden Layer

10 nodes at output Layer

####Activation function:
Sigmoid

####Output function:
LogSoftMax

####Loss function:
Negative Log Likelihood

####Training Epoch:
5

####Regularization:
Not used


####Trainset error: **1.3352%**

####Testset accuracy: **64.08%**
