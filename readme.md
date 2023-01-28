# ENEE633 Project 2
## Instructions to run the code
### Dependencies
1. the following libraries must be installed for python 3
 - numpy
 - sklearn
 - pandas
 - numpy
 - mnist-python
 - libsvm
 - torch
 - torchvision
 - matplotlib
 - random

2. the mnist directory must be placed in the same level as the p1.ipynb file.
3. Mnist must be unzipped and placed in a folder named 'mnist'. 
the contents of mnist should be
t10k-images-idx3-ubyte
t10k-labels-idx1-ubyte
train-images-idx3-ubyte
train-labels-idx1-ubyte
special attention should be given to the names as they usually need to be changed from internet downloads
### SVM
1. every cell until the 'pick classifier' cell must be run before attempting to classify anything.
2. the classifier picking cell has comments that direct the user to commenting/uncommenting the
right lines that enable the right combination of kernel, dimensionality reduction and kernel configuration
3. to test without pca, after pca has been run once, the 'undo pca' cell has to be run followed by
the import mnist data cell
### Logistic Regression
1. the pick classifier cell contains options to run logistic regression classifier.
2. the instructions for undoing pca are the same.
3. avoid hilighting svm and logistic at the same time.
### MNIST Convolutional Neural Network
1. Pick cnn from the classifier selection cell with commenting/uncommenting of options.
2. undoing pca will need instructions from above

### Dependencies:
1. The project was implemented using Pytorch 1.13+cuda116 (matches colab in Dec 2022)
2. Python 3.8.10
3. requires the following to be present in the system
 - torch
 - torchvision
 - pathlib
 - os
 - matplotlib.pyplot as plt
 - time
 - copy
### Setup
1. place the p2.ipynb file in the same directory as the unzipped archive folder that contains the monkey dataset.
2. to run the saved model, monkey_cnn.pth should also be placed in the same directory as the .ipynb file
### Monkey Convolutional Neural Network
1. This can be run in the sequence presented in the jupyter notebook.
2. to load the saved model of monkey_cnn, uncomment the save/load model block which is labeled in code with markdown
### Monkey + Frozen VGG19
1. to skip to this part of the code, run the first 4 cells and then move to the VGG section of the code
### Monkey + UnFrozen VGG19
1. this must be run after the monkey_frozenVgg16 code from the previous part has executed


### Please reach anikk@umd.edu if any part of the program fails!