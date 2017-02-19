# About
This repository is based in the onlinebook http://neuralnetworksanddeeplearning.com by Michael Nielsen.

All the handwritten digits data sets are in mnist.pkl.gz.

This is the update version working in python 3.52 writed by Daniel Dobrzanski

 <html><a href = "https://github.com/MichalDanielDobrzanski/DeepLearningPython35  ">here</a></html>



just go along in the next lines in your python shell.

>>> import mnist_loader

>>> training_data, validation_data, test_data = \

... mnist_loader.load_data_wrapper()

>>> import network

>>> net = network.Network([784, 30, 10])

>>> net.SGD(training_data, 30, 10, 3.0, test_data=test_data)



Then, you should see something like this:

Epoch 0: 9129 / 10000

Epoch 1: 9295 / 10000

Epoch 2: 9348 / 10000

...

Epoch 27: 9528 / 10000

Epoch 28: 9542 / 10000

Epoch 29: 9534 / 10000


The porpuse of this repository is use tunning algorithms for inicial weights and rewrite this algorithm for handwritting letter recognition.
