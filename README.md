
## Project Overview

It is the Dog-Breed classification project from the Deep Learning Nanodegree program of Udacity. This project is based on Convolutional Neural Networks (CNN) and it can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.  

## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
	git clone https://github.com/HebertoMadrigalSastre/DLND_P2_Dog-Breed_Classifier.git

	cd DLND_P2_Dog-Breed_Classifier
	```

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the DLND_P2_Dog-Breed_Classifier repository, at the location `data/dog_images`.

3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz). Unzip the folder and place it in the DLND_P2_Dog-Breed_Classifier repository, at the location `data/lfw`.

4. Verify that you have already installed the required Python packages:

	- jupyter notebook
	- pytorch
	- opencv
	- numpy
	- matplotlib
	- pillow
	- tqdm


5. Open the notebook dog_app.ipynb file.
	
	```
	jupyter notebook dog_app.ipynb
	```

## Project content

The project is based on the following steps: 

- Intro
- Step 0: Import Datasets
- Step 1: Detect Humans
- Step 2: Detect Dog
- Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
- Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
- Step 5: Write Your Algorithm
- Step 6: Test Your Algorithm


## (Optionally) Accelerating the Training Process

If the execution of the code is taking too long, you'd like to use a GPU. You can use Amazon Web Services to launch an EC2 GPU instance.