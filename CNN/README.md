##Convolutional Neural Network Model


* Architecture
  1. Convolutional layer with 6 filters of 5 x 5 size on 3 channel input, stride 1, no padding. 
  2. Pooling layer with 2 x 2 kernel, stride 1
  3. Convolutional layer with 16 filters of 5 x 5 size on 6 channel input, stride 1, no padding.
  4. Pooling layer with 2 x 2 kernel, stride 1
  5. Fully connected layer
    1. 256 neurons
    2. 120 neurons
    3. 84 neurons
  6. 10 output Neurons
* Activation Used: ReLU
* Loss Function: Negative log likelihood
* Learning algorithm: Stochastic Gradient
* Training Error: 0.034
* **Test Accuracy: 98%**
