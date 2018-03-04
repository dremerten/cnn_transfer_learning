# Transfer Learning on CNNs

## Introduction
The following project provides a glimpse into the advantages of using transfer Learning when building convolutional neural network (CNN) models. The CNN built is trained to classify dog breeds based on image inputs and attempts to find a suitable model by analyzing different model architectures and employing transfer learning along the way.

Much of the work produced here was inspired by [one of my Udacity Artificial Intelligence Nanodegree projects](https://github.com/grantathon/dog_breed_image_classifier).

[Display notebook](http://nbviewer.jupyter.org/github/grantathon/cnn_transfer_learning/blob/master/transfer_learning.ipynb)

## Setup
Complete the following steps to run the Jupyter notebook:

1. Install the necessary packages. For GPU support, use ```requirements-gpu.txt```.
```
virtualenv -p python3 env
source env/bin/activate
pip install -r requirements.txt
```
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip) and unzip at the project root directory.
3. Switch Keras backend to TensorFlow.
	- __Linux__ or __Mac__: 
		```
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
		```
	- __Windows__: 
		```
		set KERAS_BACKEND=tensorflow
		python -c "from keras import backend"
		```
## Run
```
jupyter notebook transfer_learning.ipynb
```
