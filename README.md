# spam_filter_with_seal
This repo is to implement the neural network for email spam classification in SEAL.
The function to implement is ((X*W1)^2)*W2, where
  X = [], vector (1 x n) of size n = 2000, 3000, 4000, 5000
  W1 = [], matrix of size (40 x n)
  W2 = [], matrix of size (20 x 40)
  
  X, W1 and W2 can be assumed as vector of integers. 
