# MNIST
This is 10 layer neural network model with 2 cnn layer and gives close to 99% accuracy on mnist dataset that is uploaded here in the pickle format.
functions to divide data into batches and extrat data from pickle file is given in utils.py and utils_train.py respectively which we will require.
I have trained it for 10 epochs you can train it for more but keep and aye on train and val accuracy and stop once it gets overfitted.
Also try to change batch size, learning rate, momentum, optimization algorithm to see if you can get better results.
To, flatten the layer i have written a function that can be found in utlis.py file.
