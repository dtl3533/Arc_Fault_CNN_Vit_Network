# arc_fault_CNN_Vit_Network

## Project Description:

This project uses arc fault dataset to classify Low voltage arc fault, using a parallel neural network structure which is based on convolutional neural network (CNN) and the Transformer.


## Data set:

- Data set name: arc fault dataset

- Data set size: about 5 GB

- File count: including train, test and vaild dataset

- Data structure: for items in h5 file, the last one is the label, and the previous data is a total of 3*25*128 sizes, each 25*128 respectively represents the low frequency current and two high frequency characteristics.

- Train code: the main training code file is 'resnet_vit.py' and the other files are used to compare the performance of these outputs.


## Result:

- Best model accuracy for CNN-VIT model: 99.74%



## Technology used:

- Deep Learning framework: pytorch



## How to run code:

Make sure you have a Python environment and the necessary libraries like pytorch for gpu, h5py, and infrequently used library like d2l. 

Taking 'resnet_vit.py' as an example. After the dependency is installed, run the following command on the terminal:

python resnet_vit.py
