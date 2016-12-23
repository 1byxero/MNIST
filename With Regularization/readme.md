##Neural Network models with L2 regularization

* Loss Function: Negative Log Likelihood
* Learning Algorithm: Stochastic Gradient

| Architecture | Activations | Epochs | L2 regularization weight | Train Error | CV Accuracy |
| --- | --- | --- | --- | --- | --- |
| 784 x 400 x 10 | Sigmoid | 5 | 5 | 0.2762% | 92.17% |
| 784 x 400 x 10 | Sigmoid | 5 | 10 | 0.2701% | 92.52% |
| 784 x 400 x 10 | Sigmoid | 5 | 13 | 0.2790% | 91.72% |
| 784 x 400 x 10 | Sigmoid | 5 | 15 | 0.2780% | 91.99% |
| 784 x 400 x 10 | Tanh | 5 | 5 | 0.5818% | 82.58% |
| 784 x 400 x 10 | Tanh | 5 | 7 | 0.5293% | 85.04% |
| 784 x 400 x 10 | Tanh | 5 | 10 | 0.5493% | 84.08% |
| 784 x 400 x 10 | Tanh | 5 | 13 | 0.5507% | 83.84% |
| 784 x 400 x 10 | ReLU | 5 | 5 | 2.3152% | 12.05% |
| 784 x 400 x 10 | ReLU | 5 | 10 | 2.3006% | 10.95% |
| 784 x 400 x 10 | ReLU | 5 | 15 | 2.2916% | 11.01% |
| 784 x 400 x 200 x 10 | Sigmoid | 10 | 5 | 0.4143% | 87.49% |
| 784 x 400 x 200 x 10 | Sigmoid | 10 | 10 | 0.4159% | 87.25% |
| 784 x 400 x 200 x 10 | Sigmoid | 10 | 15 | 0.4446% | 85.89% |
| 784 x 400 x 200 x 10 | Tanh | 10 | 5 | 0.5976% | 80.35% |
| 784 x 400 x 200 x 10 | Tanh | 10 | 10 | 0.5436% | 82.84% |
| 784 x 400 x 200 x 10 | Tanh | 10 | 15 | 0.6142% | 74.075% |
| 784 x 400 x 200 x 10 | ReLU | 10 | 5 | 0.04221% | 96.44% |
| 784 x 400 x 200 x 10| ReLU | 10 | 10 | 0.0339% | 96.72% |
| 784 x 400 x 200 x 10 | ReLU | 10 | 15 | 0.0524% | 96.6125% |
