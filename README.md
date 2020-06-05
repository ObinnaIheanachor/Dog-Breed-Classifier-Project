# Dog-Breed-Classifier-Project
Udacity Dog Breed Classifier Project

![](https://github.com/udacity/deep-learning-v2-pytorch/blob/master/project-dog-classification/images/sample_dog_output.png)

This repo contains my work for the Dog Breed Classifier Project from Udacity's Deep Learning Nanodegree. In this project, I have learnt how to build algorithms to process real-world, user-supplied images with both transfer learning using pre-trained models as well as building a CNN model from scratch. Given a dog's image, the algorithm will identify the dog’s breed and if given an image of a human, the code will identify the resembling dog breed. Along with exploring state-of-the-art CNN models for classification, I have made important design decisions about the user experience for the dog app. By completing this lab, I understood the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline. Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.

## Project Instructions
Instructions
Clone the repository and navigate to the downloaded folder.

	git clone https://github.com/udacity/deep-learning-v2-pytorch.git
	cd deep-learning-v2-pytorch/project-dog-classification
NOTE: if you are using the Udacity workspace, you DO NOT need to re-download the datasets in steps 2 and 3 - they can be found in the /data folder as noted within the workspace Jupyter notebook.

Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages. The dogImages/ folder should contain 133 folders, each corresponding to a different dog breed.

Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz). Unzip the folder and place it in the repo, at location path/to/dog-project/lfw. If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder.

Make sure you have already installed the necessary Python packages according to the README in the program repository.

Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.

	jupyter notebook dog_app.ipynb
NOTE: While some code has already been implemented to get you started, you will need to implement additional functionality to successfully answer all of the questions included in the notebook. Unless requested, do not modify code that has already been included.

NOTE: In the notebook, you will need to train CNNs in PyTorch. If your CNN is taking too long to train, feel free to pursue one of the options under the section Accelerating the Training Process below.

(Optionally) Accelerating the Training Process
If your code is taking too long to run, you will need to either reduce the complexity of your chosen CNN architecture or switch to running your code on a GPU. If you'd like to use a GPU, you can spin up an instance of your own:

Amazon Web Services
You can use Amazon Web Services to launch an EC2 GPU instance. (This costs money, but enrolled students should see a coupon code in their student resources.)

## License
The contents of this repository are covered under the [MIT License](https://github.com/ObinnaIheanachor/Dog-Breed-Classifier-Project/blob/master/LICENSE)

