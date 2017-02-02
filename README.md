## Collection of kaggle competition scripts and kernels.
	Contains scripts for different deep learning models including CNN, VGG, XGBoost, PCA + SVM....

## Rig Configuration,Requirements/Dependencies.
	Python 3.5 or 2.7
	Anaconda 3.5
	CUDA 7.5
	Numpy, Scipy.
	Keras (Tensorflow backend).
	Tensorflow.
	Scikit-learn.
	Pandas.
	OpenCV

# For every script there are two versions -->
	1. Full model scripts to run on local/personal machine --> " _fm "
	2. Limited model scripts capable of running on kaggle kernels (since kaggle servers are timed-out after 20minutes) --> " _lm "
	
# Most of these scripts have been executed on a GPU enabled laptop and have also been tested on the kaggle kernels (servers).

## Competition 1 -> Level Beginner.
	Digit Recognizer --> MNIST
		- Convolutional neural networks perform the best, with the VGG-like networks but the require largest amount of time. 
		- SqueezeNet is fast to train but does not perform as well as VGG.

## Competition 2 -> Level Beginner.
	Titanic: Machine Learning from Disaster --> Survival Prediction
		- XGBoost is the best performing model here.
	
## Competition 3 -> Level Intermediate.
	Dogs vs. Cats Redux : Kernels Edition --> Distinction Dogs vs Cats.
		- 
		- 

## Competition 4 -> Level Intermediate.
	The Nature Conservancy Fisheries Monitoring --> Fish Classification.
		- 
		- 

## Competition 5 -> Level Difficult.
	Data Science Bowl 2017 --> Lung Cancer detection.
		- The most challenging part for this is the pre-processing due to the heterogeneous nature of the data.
		- Here we are predicting whether a CT scan is of a patient who either has or will develop cancer within the next 12 months       or not.
