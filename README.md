# CIFAR10 Image Classification using different Deep Learning Techniques

This repo is for the term project for Data Mining course.

Dataset Used: CIFAR10 dataset
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

Visit https://www.cs.toronto.edu/~kriz/cifar.html to download the dataset 


Goal:

Classify images from 10 different classes for CIFAR10 dataset.

How to Run the Project:

The project code is located at the main directory. There are five .ipynb files for baseline model, VGG16 model, ResNet18 model, Squeezenet model and DenseNet  model named "Image_classification_baseline.ipynb", "Image_classification_VGG16.ipynb", "Image_Classification_ResNet18.ipynb", "Image_Classification_Squeezenet.ipynb", and "Image_Classification_Densenet.ipynb" respectively.  Since this is a copy of google colab file, to run each section of the code, a person only needs to sign in to google drive and run the code. Otherwise if anyone want to download a copy they just need to have the Jupyter Notebook environment installed in their device and then open the file and click on 'Run' to see output for that code section (database will automatically download in the device).

Make sure you have the following packages available/installed:

PyTorch
Tensorflow
NumPy
Pandas
To install a specific library from Jupyter notebook directly, the following link is helpful:

https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/
Usually Anaconda distribution is installed with most of these packages, so running Jupyter notebook from Anaconda is recommended.
