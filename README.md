# Training-a-CNN-on-the-CIFAR10-dataset

CIFAR10 is a dataset containing 60000 images in 10 classes(plane, car, bird, cat, deer, dog, frog, horse, ship, truck).
The goal is to train a CNN so that given a new image not seen before, the network will be able to tell you which class 
the image belongs to amongst the 10 classes above.

![Images from CIFAR10](https://github.com/SohrabSamimi/Training-a-CNN-on-the-CIFAR10-dataset/blob/main/cifar10.png)

We also compute the global accuracy of the network: given a dataset of new images in the 10 classes, how many times does
the network predict the right class? The answer is around 6 times out of 10 ( 61% accuracy).

After, we compute the model accuracy for each of the 10 classes. For instance the class car has 74% accuracy.


This repository is strongly inspired by the Pytorch tutorial called "Training a Classifier" at the following link:
https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html
           
I first understood the code from the tutorial, and then rewrote the code myself to train the CNN on CIFAR-10.
I also changed several hyperparameters from the Pytorch tutorial.
