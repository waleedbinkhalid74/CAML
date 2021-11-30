# Computational Aspects of Machine Learning - By Waleed Bin Khalid

This experiment is in conjunction with the paper submitted for the seminar **Computational Aspects of Machine Learning** at the Technical University of Munich. We compare the some numerical optimizers with respect to their accuracy and time complexity with the help of a simple example. We train a convolutional neural network to classify the well-known MNIST dataset which consists of 60,000 $28 \times 28$ pixel images of hand drawn numbers. We keep all the parameters of our neural network the same except for the Numerical Optimizer utilized to train the network and observe the empirical results.

Source: This experiment was taken from https://nextjournal.com/gkoehler/pytorch-mnist and edited to suit experimentation needs.

### We analyze the following Numerical Optimizers in this experiment with the aid of the well known MNIST dataset.
1. SGD
2. SGD with Momentum
3. Nesterov Momentum
4. Adagrad
5. ADAM
6. LBFGS
8. Hessian Free
9. Newton-CG
