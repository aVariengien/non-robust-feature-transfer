
# Non-robust features transfer for a new adversarial attack against neural image classifiers
### By Alexandre Variengien


### Context

This repository contains the code used in the project of the CS-503 course "Visual Intelligence: machines and mind" at EPFL. The full report of the project can be found as a pdf [here](https://raw.githubusercontent.com/aVariengien/non-robust-feature-transfer/ca3d037969434bb40d9f462c6e18a29f9e4f60b1/Non-Robust-Feature-Transfer.pdf).


### Instruction

This project implement a new adversarial attack again classifiers. The goal is to
make them classify images humans cannot see.

The attack can be directly reproduced on the CIFAR10 dataset against 3 models in a Colab notebook. Try it now [here](https://colab.research.google.com/github/aVariengien/non-robust-feature-transfer/blob/master/CIFAR10-Non_Tobust_Features_Transfer.ipynb)!

I also included the notebook used to perform the ImageNet dataset. To be run, it need to be next to a folder
called `ImageNet` containing images in folders corresponding to classes.
