# About
This repository is based in the online book http://neuralnetworksanddeeplearning.com by Michael Nielsen 
All the handwritten digist can be found in mnist.pkl.gz, but here is working in python 3.x is support by https://github.com/MichalDanielDobrzanski/DeepLearningPython35  

just go along in the next line in your python shell.

>>> import mnist_loader
>>> training_data, validation_data, test_data = \
... mnist_loader.load_data_wrapper()
>>> import network
>>> net = network.Network([784, 30, 10])
>>> net.SGD(training_data, 30, 10, 3.0, test_data=test_data)
Epoch 0: 9129 / 10000
Epoch 1: 9295 / 10000
Epoch 2: 9348 / 10000
...
Epoch 27: 9528 / 10000
Epoch 28: 9542 / 10000
Epoch 29: 9534 / 10000
