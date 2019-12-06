# Dog Breed Classifier with PyTorch

## Project Overview

Hello there !

Artificial Neural Networks have rapidly growing applications in the area of image-based classification problems. Moreover, recent advances in the ANN technology allows for the use/reuse of pre-trained Deep Artificial Neural Networks (e.g. AlexNet, Resnet, VGG, and others) that were trained to recognize thousands of different categories by sifting through millions of high resolution images. This re-utilization of pretrained Deep Neural Networks belongs to a field of Machine Learning called “Transfer Learning” where these pre-built models can be repurposed to be utilized in numerous applications of image recognition and classification.

Recognizing the breeds of dogs is certainly a challenging task. The estimated number of known dog breeds ranges between 200 and 350 different breeds, making the task of telling “which breed a dog belongs to” a very challenging task. This task gets more difficult when the breeds are visually similar and cannot be easily distinguished.


This project is to showcase the use of Deep Learning with a pretrained VGG16 Deep Neural Network for the classification of dog breeds from dog images using PyTorch.

This project was developed as part of the requirements the Deep Learning NanoDegree program offered by Udacity.

## Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/udacity/deep-learning-v2-pytorch.git
		cd deep-learning-v2-pytorch/project-dog-classification
	```
    
__NOTE:__ if you are using the Udacity workspace, you *DO NOT* need to re-download the datasets in steps 2 and 3 - they can be found in the `/data` folder as noted within the workspace Jupyter notebook.

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
4. Make sure you have already installed the necessary Python packages according to the README in the program repository.
5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dog_app.ipynb
	```

__NOTE:__ In the notebook, you will need to train CNNs in PyTorch.  If your CNN is taking too long to train, feel free to pursue one of the options under the section __Accelerating the Training Process__ below.



## (Optionally) Accelerating the Training Process 

If your code is taking too long to run, you will need to either reduce the complexity of your chosen CNN architecture or switch to running your code on a GPU.  If you'd like to use a GPU, you can spin up an instance of your own:

#### Amazon Web Services

You can use Amazon Web Services to launch an EC2 GPU instance. (This costs money, but enrolled students should see a coupon code in their student `resources`.)
